## hadoop-HBase

In this post, I will talk about Hbase. I will cover the following topics:  
- HBase overview
- j

**HBase overview**  
_HBase_ is an open source, non-relational, distributed database modeled after Google's BigTable and written in Java. HBase can perform faster thant HDFS when random, real-time read/write access to Big Data is needed.

_HBase VS HDFS:_   
- HDFS does not support fast individual record lookups -> HBase provides fast lookups for large tables
- HDFS have high latency batch processing -> HBase have low latency access to single rows from billions of records
- HDFS have sequential access of data only -> HBase internally uses Hash tables and provides random access



