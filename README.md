# Big_Data_Partitioning_461
Big Data storage and partitioning system test


In this project, we simulate a Big Data storage and partitioning system using a real-world dataset.
The goal is to explore how different data partitioning techniques affect data retrieval performance.

The dataset used in this project is available on Google Drive:
Heart Disease Dataset: https://drive.google.com/file/d/1mKJTBpewpqo6f63si58oARqIK62mJW3h/view?usp=sharing

🎯 Objectives

Store columnar data from the dataset using pandas and numpy.

Implement three partitioning methods commonly used in Big Data systems:

Range Partitioning – dividing data based on value ranges (e.g., age intervals).

List Partitioning – dividing data based on categorical attributes (e.g., target values).

Hash Partitioning – distributing data based on hash functions (e.g., age % n).

Measure and compare search performance:

Compute the number of iterations required to locate a specific element (e.g., age = 77)
in the original dataset versus the partitioned datasets.

Append new records to each partitioning type to simulate data insertion operations.

Visualize and compare the performance of the different partitioning techniques using bar charts.

💡 Expected Outcome

By the end of this project, you will:

Understand how different partitioning strategies organize data.
Observe how partitioning can improve data retrieval efficiency.
Simulate real-world data before deployment in Big Data systems like Apache Hive, Spark, and distributed databases.
