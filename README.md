
# Apache-Spark-Project-and-Hadoop

In this project, I've crafted a PySpark project typically involves using the PySpark library in Python to process and analyze large datasets using Apache Spark.




## Hadoop 

Hadoop is an open-source framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It consists of two main components: the Hadoop Distributed File System (HDFS) for storage, and the MapReduce programming model for processing. Hadoop is designed to scale from a single server to thousands of machines, each offering local computation and storage. It provides a cost-effective and efficient way to store, process, and analyze big data.

![App Screenshot](https://github.com/VennapusaManoj1998/Apache_Spark_Project/blob/main/Hadoop.jpeg)

Hadoop Distributed File System (HDFS) and MapReduce are the two main pillars of the Apache Hadoop framework

#### HDFS

HDFS is the storage unit of Hadoop, while MapReduce is the processing unit. HDFS stores data in blocks that are either 64 MB or 128 MB in size. 

HDFS has a global view of files, even if they are spread across cluster nodes.

![App Screenshot](https://github.com/VennapusaManoj1998/Apache_Spark_Project/blob/main/map_reduce.png)

#### MapReduce

MapReduce is a Java-based framework that processes data in HDFS. It's a submodule of Apache Hadoop that's used to process large data sets. 
	
MapReduce is a programming model that reduces data on each mapper to a simplified form before passing it downstream. This makes it easier to sort and shuffle data.

## Apache Spark

Apache Spark is a fast and versatile open-source distributed computing system. It provides an interface for programming clusters with data parallelism and fault tolerance, supporting various tasks like batch processing, interactive queries, streaming analytics, and machine learning. Spark is designed to be efficient and can run on Hadoop, standalone, or in the cloud, accessing diverse data sources.

![App Screenshot](https://github.com/VennapusaManoj1998/Apache_Spark_Project/blob/main/spark.jpg)

Apache Spark is an open-source, distributed computing system for big data processing and analytics. It can handle both batch and real-time data processing workloads

Apache spark is cluster computing framework or you can say it is processing engine, which is 10 times faster than Mapreduce because spark uses in memory(Cache) computation whereas Mapreduce deals with Disk. Spark avoids I/O operations with disk which is time consuming task. The main feature of Spark is its in-memory cluster computing that increases the processing speed of an application.

![App Screenshot](https://github.com/VennapusaManoj1998/Apache_Spark_Project/blob/main/Hadoop-vs-Spark.jpg)

Hadoop stores and processes data on external storage. Spark stores and process data on internal memory.









