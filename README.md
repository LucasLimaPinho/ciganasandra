# ciganasandra

[Apache Cassandra](https://cassandra.apache.org/)

Apache Cassandra is a Partition Row store NoQl Database. The data is distributed by partitions across nodes or servers and the data is organized in the columns and rows format.

* Keyspace: collection of tables; In relational terms, would be a database;

* Table: a group of partitions;

* Rows: a single item

* Partition: fundamental unit of access; Is a collection of rows and is how data is distributed.

* Primary Key: Primary key is made up of a partition key and clustering columns

* Column: Labeled element. There is Clustering Columns and Data Columns.

Apache Cassandra provides scalability and high availablity without compromising performance. Apache Cassandra uses it own query language (CQL - Cassandra Query Language)

When you add nodes, Apache Cassandra will increase its performance in a linear fashion (Horizontal Scalling).

**There are no duplicates in Apache Cassandra**: The combination of PartitionBy and Clustering Column will make each Primary Key unique. If you don't have a unique key, it will just get overwritten. 


