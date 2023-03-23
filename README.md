# column-family-database

HBase is an open-source, distributed, column-oriented NoSQL database management system that runs on top of the Hadoop Distributed File System (HDFS). It is designed to handle large amounts of structured or semi-structured data, and provides low-latency, random access to the data stored in it. HBase is modeled after Google's Bigtable, and it is well-suited for use cases where fast data access, high availability, and scalability are essential.


                                                   #Project Name: HBase Data Creation

#Description:

This project involves creating data and inserting values into tables in HBase, an open-source, non-relational distributed database that runs on top of the Hadoop Distributed File System (HDFS).

Table Schema:

                                                         cust1 - with columns 'name', 'hmtp', and 'loc'
                                                         consult - with column 'loc'
                                                         lab - with columns 'name', 'dow', and 'slry'
                                                         mat - with columns 'steel', 'door', 'ratio', 'rt', and 'pip'


Data Creation Steps:

#Creating Tables:
To create tables, 'create' is used command followed by the table name and column families separated by commas.


#Inserting Data:
To insert data, 'put' is used command followed by the table name, row key, column family, column qualifier, and value separated by commas


#Updating Data:
To update data similar to inserting, 'put' is used command followed by the table name, row key, column family, column qualifier, and value separated by commas

#Deleting Data:
To delete data, 'delete' is used command followed by the table name and column families separated by commas.

Tables in this Project:
