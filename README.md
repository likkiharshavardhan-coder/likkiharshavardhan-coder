# 👋 Hi, I'm Harsha Likki

### 🚀 Data Engineer | PySpark | Python | SQL | AWS | Databricks

Data Engineer with **3+ years of experience** in developing and supporting scalable data pipelines, ETL workflows, and distributed data processing solutions. Experienced in transforming structured and semi-structured data using Python, PySpark, Apache Spark, SQL, and AWS.

- 🔭 Working with data engineering concepts, ETL pipelines, and big data processing
- 🌱 Exploring Databricks, Delta Lake, and AI-assisted development
- 💻 Practicing SQL and PySpark through hands-on coding scenarios
- ⚡ Interested in Spark optimization, incremental processing, data quality, and distributed computing
- 🤝 Open to collaborating on data engineering and open-source projects
- 📍 Hyderabad, India

---

## 🛠️ Technical Skills


## 🛠️ Technical Skills


### ⚡ Big Data & Processing
<p align="left">
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/PySpark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=black" />
  <img src="https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black" />
  <img src="https://img.shields.io/badge/Apache%20Hive-FDEE21?style=for-the-badge&logo=apachehive&logoColor=black" />
</p>

### ☁️ Cloud & Data Platforms
<p align="left">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20EMR-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20Glue-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Delta%20Lake-00ADD8?style=for-the-badge&logo=deltalake&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon%20Athena-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
</p>

### 🔄 Workflow Orchestration
<p align="left">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
</p>

### 🔧 Development Tools
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

### 🧩 Core Data Engineering
- ETL/ELT Pipelines
- Batch & Incremental Processing
- Data Cleansing & Validation
- Data Quality Checks
- Data Lake Architecture
- Spark Optimization


**Languages:** Python, SQL

**Big Data Technologies:** Apache Spark, PySpark, Spark SQL, Hadoop, Hive

**Cloud & Data Platforms:** AWS, Amazon S3, AWS EMR, AWS Glue, Databricks, Delta Lake, Amazon Athena

**Workflow Orchestration:** Apache Airflow

**Data Engineering:** ETL/ELT, Batch Processing, Incremental Data Processing, Data Cleansing, Data Validation, Data Quality, Data Lake Architecture

**Tools:** Git, GitHub, Linux

---

## 📂 Featured Repository

### 🔹 SQL & PySpark Use Cases

A collection of SQL and PySpark practice scenarios covering data filtering, transformations, aggregations, joins, and analytical functions.

📌 **Explore my repository:**  
[SQL-DFS-USE-CASE](https://github.com/likkiharshavardhan-coder/SQL-DFS-USE-CASE)

**Topics covered:**
- Filtering with `WHERE`, `AND`, `IN`, `LIKE`, and null conditions
- Aggregations using `SUM`, `COUNT`, `MIN`, and `MAX`
- Conditional transformations using `CASE WHEN`
- String operations such as `CONCAT`, `TRIM`, `SPLIT`, `LOWER`, and `UPPER`
- Joins: INNER, LEFT, RIGHT, FULL, LEFT ANTI, and CROSS
- Window functions: `ROW_NUMBER`, `RANK`, `DENSE_RANK`, `LAG`, and `LEAD`
- Grouping, sorting, `HAVING`, `UNION`, and `UNION ALL`
- Implementing equivalent operations using SQL and PySpark DataFrames

---

## 💻 Sample SQL & PySpark Code

### 1. Filtering Data

```python
df.filter(
    (df.category == "Exercise") &
    (df.spendby == "cash")
).show()
```

### 2. Aggregations

```python
from pyspark.sql.functions import sum, count

df.groupBy("category", "spendby").agg(
    sum("amount").alias("total_amount"),
    count("amount").alias("record_count")
).show()
```

### 3. Window Functions

```python
from pyspark.sql import Window
from pyspark.sql.functions import col, row_number

window_spec = Window.partitionBy(
    "category"
).orderBy(col("amount").desc())

df.withColumn(
    "row_num", row_number().over(window_spec)
).show()
```

### 4. DataFrame Joins

```python
joined_df = cust.join(
    prod, on="id", how="left"
)

joined_df.show()
```

---

## 🤝 Connect With Me

- 💼 **LinkedIn:** [linkedin.com/in/likki-harsha-vardhan-b4a583252](https://www.linkedin.com/in/likki-harsha-vardhan-b4a583252)
- 💻 **GitHub:** [likkiharshavardhan-coder](https://github.com/likkiharshavardhan-coder)
- 📧 **Email:** likkiharshavardhan@gmail.com

---

⭐ *Building data-driven solutions, solving problems, and continuously learning new technologies.*
