# ApacheSparkRecipee
A collection of code I will use in the next 02 years GOAL: become proficient in Apache Spark and Hadoop

## MapReduce:

A simple mapreduce job written in python and executed on hadoop:

`cd /usr/local/hadoop && bin/hadoop jar /usr/local/hadoop/lib/hadoop-streaming-2.7.1.jar  -file mapper.py -mapper mapper.py -file reducer.py -reducer reducer.py -input /pathToYourData  -output /PathToOutput`
