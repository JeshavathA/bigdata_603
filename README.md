# Working with Crime Data using Apache Spark

In this assignment, we'll explore crime data using Apache Spark, a powerful framework for big data processing. We'll perform various tasks to analyze and gain insights from the Chicago crime dataset.

## Task 1: Create a Spark Session

The first step is to set up a Spark session to work with the data efficiently:

```python
from pyspark.sql import SparkSession

spark = SparkSession.builder.appName("CrimeAnalysis").getOrCreate()
