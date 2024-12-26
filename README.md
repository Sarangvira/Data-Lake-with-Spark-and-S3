# Data-Lake-with-Spark-and-S3

## Description

This repo provides the ETL pipeline, to populate the sparkifydb AWS S3 Data Lake using Spark

The purpose of this database is to enable Sparkify to answer business questions it may have of its users, the types of songs they listen to and the artists of those songs using the data that it has in logs and files. The database provides a consistent and reliable source to store this data.

This source of data will be useful in helping Sparkify reach some of its analytical goals, for example, finding out songs that have highest popularity or times of the day which is high in traffic.

For the ETL pipeline, Python is used as it contains libraries such as pandas, that simplifies data manipulation. It enables reading of files from S3, and data processing using Pyspark.

There are 2 types of data involved, song and log data. For song data, it contains information about songs and artists, which we extract from and load into users and artists dimension tables

Log data gives the information of each user session. From log data, we extract and load into time, users dimension tables and songplays fact table.
