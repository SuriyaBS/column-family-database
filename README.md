# column-family-database

HBase is an open-source, distributed, column-oriented NoSQL database management system that runs on top of the Hadoop Distributed File System (HDFS). It is designed to handle large amounts of structured or semi-structured data, and provides low-latency, random access to the data stored in it. HBase is modeled after Google's Bigtable, and it is well-suited for use cases where fast data access, high availability, and scalability are essential.

HBase is different from traditional relational databases in several ways. First, it is a NoSQL database, which means that it does not use the traditional table-based schema of a relational database. Instead, it stores data in a distributed, column-oriented fashion, allowing for very fast reads and writes. Second, HBase is designed to be highly scalable, allowing it to store and process massive amounts of data across many commodity servers. Third, HBase provides strong consistency guarantees, ensuring that all reads and writes are consistent and accurate across the cluster. Finally, HBase is designed to work with Hadoop, and it can be used in conjunction with other Hadoop ecosystem tools, such as Apache Spark and Apache Hive, to process and analyze large data sets



Project Name: HBase Data Creation

Description:
This project involves creating data and inserting values into tables in HBase, an open-source, non-relational distributed database that runs on top of the Hadoop Distributed File System (HDFS).

Table Schema:

     cust1 - with columns 'name', 'hmtp', and 'loc'
     consult - with column 'loc'
     lab - with columns 'name', 'dow', and 'slry'
     mat - with columns 'steel', 'door', 'ratio', 'rt', and 'pip'


Data Creation Steps:

Creating Tables:
To create tables, use the 'create' command followed by the table name and column families separated by commas.

Inserting Data:
To insert data, use the 'put' command followed by the table name, row key, column family, column qualifier, and value separated by commas
