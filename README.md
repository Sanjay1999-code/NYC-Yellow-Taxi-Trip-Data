Apache Spark Data Engineering Project

Dataset

- Dataset Name: nyc yellow taxi trip data 
- Source: Kaggle
- Dataset URL: https://www.kaggle.com/datasets/elemento/nyc-yellow-taxi-trip-data

Project Objective

The objective of this project is to perform data engineering operations using Apache Spark in Databricks. The dataset is loaded, explored, cleaned, transformed, and saved in Parquet format.

Steps Performed

1. Downloaded the dataset from Kaggle.
2. Uploaded the dataset to Databricks.
3. Read the dataset using PERMISSIVE mode.
4. Explored the data by printing column names, row count, schema, and number of columns.
5. Checked for corrupted records.
6. Applied data transformations such as adding columns, renaming columns, filtering, casting data types, and removing unnecessary columns.
7. Identified and handled null values.
8. Removed duplicate records.
9. Saved the processed dataset in Parquet format using overwrite mode.

Transformations Used

- Added new columns using "withColumn()"
- Renamed columns using "withColumnRenamed()"
- Filtered rows using "filter()"
- Cast data types using "cast()"
- Removed unnecessary columns using "drop()"
- Removed duplicate rows using "dropDuplicates()"
- Filled null values using "fillna()"

Output

The processed dataset was successfully stored in Parquet format.

Challenges Faced

- Handling null values.
- Checking for corrupted records.
- Choosing appropriate transformations.
- Saving the processed data in an efficient format.

Technologies Used

- Apache Spark (PySpark)
- Databricks
- Python
