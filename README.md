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


 Commands Used in this Project:

Creating 'cust1' table with column families 'name', 'hmtp', and 'loc'
create 'cust1','name','hmtp','loc'

Inserting values into 'cust1' table:

  put 'cust1','0193','name','anu'
  put 'cust1','4567','name','vino'
  put 'cust1','2389','name','prem'
  put 'cust1','0193','hmtp','2bhk'
  put 'cust1','4567','hmtp','1bhk'
  put 'cust1','2389','hmtp','1bhk'
  put 'cust1','0193','loc','palani'
  put 'cust1','4567','loc','erode'
  put 'cust1','2389','loc','tirupur'

Creating 'consult' table with column family 'loc'
create 'consult','loc'

Inserting values into 'consult' table:

  put 'consult','bob','loc','chennai'
  put 'consult','sbi','loc','ooty'
  put 'consult','kvb','loc','karur'

Creating 'lab' table with column families 'name', 'dow', and 'slry'

  create 'lab','name','dow','slry'

Inserting values into 'lab' table:

  put 'lab','supervisor','name','kani'
  put 'lab','helper','name','ruba'
  put 'lab','helper','name','ranjith'
  put 'lab','supervisor','dow','241'
  put 'lab','helper','dow','200'
  put 'lab','helper','dow','198'
  put 'lab','supervisor','slry','45000'
  put 'lab','helper','slry','43000'
  put 'lab','helper','slry','38000'

Creating 'mat' table with column families 'steel', 'door', 'ratio', 'rt', and 'pip'

  create 'mat','steel','door','ratio','rt','pip'

Inserting values into 'mat' table:

  put 'mat','m20','steel','30tmt'
  put 'mat','m30','steel','20tmt'
  put 'mat','m80','steel','10tmt'
  put 'mat','m20','door','pw'
  put 'mat','m30','door','wpc'
  put 'mat','m80','door','sow'
  put 'mat','m20','ratio','1:1:5:3'
  put 'mat','m30','ratio','1
