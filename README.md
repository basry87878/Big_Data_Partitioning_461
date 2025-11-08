# Big_Data_Partitioning_461
Big Data storage and partitioning system test

In this project, we simulate a Big Data storage and partitioning system using a real-world dataset.
The main goal is to explore how different data partitioning techniques influence data retrieval performance and scalability.

📂 Dataset

We use the Heart Disease Dataset, publicly available on Google Drive: https://drive.google.com/file/d/1mKJTBpewpqo6f63si58oARqIK62mJW3h/view?usp=sharing

🎯 Objectives

Store columnar data using pandas and numpy to simulate a columnar Big Data system.

Implement and test three partitioning techniques:

Range Partitioning – divide records based on continuous value ranges (e.g., age intervals).

List Partitioning – separate records based on categorical attributes (e.g., target classes).

Hash Partitioning – distribute records across partitions using hash functions (e.g., age % n).

Measure data retrieval performance:

Calculate the number of iterations required to find a specific element (e.g., age = 77) before and after partitioning.

Simulate data insertion by appending new records into each partition type.

Visualize and compare the performance of all partitioning techniques using bar charts.

💡 Expected Outcome

By completing this project, you will:

Understand how Range, List, and Hash partitioning organize and store data.
Observe how partitioning can reduce search iterations and improve lookup efficiency.
Gain insight into how these methods prepare data before deployment.
Build a reproducible experiment demonstrating how partitioning strategies impact performance in a simplified environment.
