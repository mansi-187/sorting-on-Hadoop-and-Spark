# Distributed Sorting and Performance Analysis using Hadoop and Apache Spark

## Overview
This project demonstrates distributed sorting techniques using Hadoop MapReduce and Apache Spark in a cloud environment. The objective is to compare the performance of Hadoop Sort and Spark Sort across large datasets of varying sizes, and evaluate their efficiency based on execution time and resource utilization.

---

## Technologies Used
- Hadoop MapReduce
- Apache Spark
- HDFS (Hadoop Distributed File System)
- Yarn (Resource Manager)
- Cloud-based Virtual Machines
- Linux Environment
- Maven

---

## Project Objectives
- Configure Hadoop Cluster on Cloud Virtual Machines
- Perform distributed sorting using Hadoop Sort and Spark Sort
- Benchmark and compare performance on datasets of 16GB, 32GB, and 64GB
- Analyze the impact of increasing RAM and VM instances on execution time
- Optimize resource allocation for better performance

---

## Directory Structure
sorting-on-hadoop-and-spark/
│
├── core-site.xml          # Hadoop core configuration
├── hdfs-site.xml          # HDFS configuration
├── yarn-site.xml          # Yarn resource manager configuration
├── mapred-site.xml        # MapReduce configuration
├── pom.xml                # Maven configuration
├── vault64GB.log          # Execution log for 64GB dataset
└── README.md              # Project documentation

