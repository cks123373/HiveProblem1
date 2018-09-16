# HiveProblem1
Perform the following tasks:

1. Copy input file from local filesystem directory/home/osgdev/Downloads to hadoop filesystem directory /user/hadoopTraining/Assignment1/input/.

[chandan@ip-20-0-41-190 ~]$ hadoop fs -put bhav040416_080416.csv Assignment1/input
[chandan@ip-20-0-41-190 ~]$ hadoop fs -ls Assignment1/input
Found 1 items
-rw-r--r--   3 chandan hadoop     730203 2018-09-16 18:29 Assignment1/input/bhav040416_080416.csv

2. Using Apache Hive create a database, an external table 'stockTrdData' in database and load this data in Hive table. Verify the data loaded by selecting first 100 rows from table.
3. Using Apache Hive queries, list symbol on each series with highest TOTTRDVAL. Copy results to local filesystem.
4. Using Apache Hive queries, list symbol on each series with highest TOTTRQTY. Check the results on Hadoop filesystem using cat command.
5. Using Apache Hive queries, list symbol on only EQ series with highest TOTTRQTY.
