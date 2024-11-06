# HADOOP-word-counting
This project shows how efficient word counting is on text data using MapReduce in Apache Hadoop. This is a classic task for continuing to work with data.  
run.txt contains a command to run via the console on Windos
# Requirements
Java (jdk)  
Apache Hadoop version 3.3.6  
Python 3.10 or later
# Installation
# Cloning a repository
```bash
git clone https://github.com/Gamabumba/HADOOP-word-counting.git
cd HADOOP-word-counting
```
# Building the project
```bash
mvn package
```
# Setting up the environment 
Make sure the HADOOP_HOME and JAVA_HOME environment variables are set correctly.
# How this work
The application consists of two main classes:  
mapper: Splits lines of text into words and outputs each word with a single meaning.  
reducer: Sums up all the individual values ​​for each word and returns the total count.  
# MapReduce Architecture
mapper: Splits text into key-value pairs (word, 1).  
reducer: Sums up the number of occurrences of each word to produce a final result.
