# Big Data & PySpark Learning Series

A complete, structured curriculum — from Hadoop fundamentals through PySpark, EDA, Streaming, and Spark MLlib. All 47 notebooks are ordered for progressive learning in a single flat folder.

> **Google Colab**: Replace `YOUR_GITHUB_USERNAME/YOUR_REPO` in badge links with your GitHub repo path.

---

## Folder Structure

```text
Pyspark/
├── Part01_*.ipynb – Part47_*.ipynb   # Ordered notebooks
├── datasets/                          # All CSV/TXT datasets
├── images/                            # Architecture diagrams
├── lib/                               # JAR files (BigQuery connector)
├── 19b.EDA-Pandas-vs-PySpark-script.py
└── README.md
```

---

## Setup

### Local

```bash
pip install pyspark findspark
jupyter notebook
```

### Google Colab

Each notebook auto-installs PySpark when running in Colab. To open:

1. Upload this folder to Google Drive → open with Colab, or
2. Push to GitHub → click a badge link below

---

## Table of Contents

### Part 1 — Big Data Foundations

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part01 | [Hadoop and Big Data Ecosystem](Part01_Hadoop%20and%20Big%20Data%20Ecosystem.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part01_Hadoop%20and%20Big%20Data%20Ecosystem.ipynb) |
| Part02 | [Hive - SQL on Hadoop](Part02_Hive%20-%20SQL%20on%20Hadoop.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part02_Hive%20-%20SQL%20on%20Hadoop.ipynb) |
| Part03 | [Hive Explore and Table Operations](Part03_Hive%20Explore%20and%20Table%20Operations.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part03_Hive%20Explore%20and%20Table%20Operations.ipynb) |

### Part 2 — PySpark Foundations

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part04 | [PySpark Architecture](Part04_Pyspark%20Architecture.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part04_Pyspark%20Architecture.ipynb) |
| Part05 | [Spark Memory Management](Part05_Spark%20Memory%20Management.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part05_Spark%20Memory%20Management.ipynb) |
| Part06 | [Introduction — Features, Streaming, GraphFrames](Part06_Introduction.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part06_Introduction.ipynb) |

### Part 3 — RDD Operations

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part07 | [RDD Transformation Types — Narrow vs Wide](Part07_RDD%20Transformation%20Types.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part07_RDD%20Transformation%20Types.ipynb) |
| Part08 | [RDD CookBook Examples — map, filter, joins, reduceByKey](Part08_RDD%20CookBook%20Examples.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part08_RDD%20CookBook%20Examples.ipynb) |
| Part09 | [PySpark map() & flatMap() Transformation](Part09_PySpark%20map()%20%26%20flatMap()%20Transformation.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part09_PySpark%20map()%20%26%20flatMap()%20Transformation.ipynb) |

### Part 4 — DataFrame Basics

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part10 | [DataFrame Basics — Schema, SparkSession, SQL](Part10_DataFrame%20Basics.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part10_DataFrame%20Basics.ipynb) |
| Part11 | [Create DataFrame and Rename with Examples](Part11_Create%20DataFrame%20and%20Rename%20with%20Examples.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part11_Create%20DataFrame%20and%20Rename%20with%20Examples.ipynb) |
| Part12 | [Select Columns From DataFrame](Part12_Select%20Columns%20From%20DataFrame.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part12_Select%20Columns%20From%20DataFrame.ipynb) |
| Part13 | [DataFrame Basic Operations — Filter, Boolean, Collect](Part13_DataFrame%20Basic%20Operations.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part13_DataFrame%20Basic%20Operations.ipynb) |
| Part14 | [Missing Data — drop(), fill(), null handling](Part14_Missing%20Data.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part14_Missing%20Data.ipynb) |
| Part15 | [Dates and Timestamps](Part15_Dates%20and%20Timestamps.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part15_Dates%20and%20Timestamps.ipynb) |
| Part16 | [GroupBy and Aggregate Functions](Part16_GroupBy%20and%20Aggregate%20Functions.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part16_GroupBy%20and%20Aggregate%20Functions.ipynb) |

### Part 5 — Advanced DataFrame Features

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part17 | [PySpark UDF (User Defined Function)](Part17_PySpark%20UDF%20(User%20Defined%20Function).ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part17_PySpark%20UDF%20(User%20Defined%20Function).ipynb) |
| Part18 | [PySpark transform() Function with Example](Part18_PySpark%20transform()%20Function%20with%20Example.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part18_PySpark%20transform()%20Function%20with%20Example.ipynb) |
| Part19 | [PySpark Pandas apply()](Part19_PySpark%20Pandas%20apply().ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part19_PySpark%20Pandas%20apply().ipynb) |
| Part20 | [Some Useful Functions — cube(), join, correlation](Part20_Some%20Useful%20Functions.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part20_Some%20Useful%20Functions.ipynb) |
| Part21 | [Creating Fake Data — Faker, sklearn synthetic datasets](Part21_Creating%20Fake%20Data.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part21_Creating%20Fake%20Data.ipynb) |

### Part 6 — Practice Projects

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part22 | [Practice — Decorators and Aggregations](Part22_Practice%20-%20Decorators%20and%20Aggregations.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part22_Practice%20-%20Decorators%20and%20Aggregations.ipynb) |
| Part23 | [Spark DataFrames Project Exercise — Walmart Stock](Part23_Spark%20DataFrames%20Project%20Exercise.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part23_Spark%20DataFrames%20Project%20Exercise.ipynb) |
| Part24 | [Spark DataFrames Project Exercise — SOLUTIONS](Part24_Spark%20DataFrames%20Project%20Exercise%20-%20SOLUTIONS.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part24_Spark%20DataFrames%20Project%20Exercise%20-%20SOLUTIONS.ipynb) |

### Part 7 — Streaming & External Integrations

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part25 | [Introduction to Spark Streaming](Part25_Introduction%20to%20Spark%20Streaming.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part25_Introduction%20to%20Spark%20Streaming.ipynb) |
| Part26 | [BigQuery Connection with PySpark](Part26_BigQuery%20Connection%20with%20PySpark.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part26_BigQuery%20Connection%20with%20PySpark.ipynb) |

### Part 8 — Machine Learning: Feature Engineering

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part27 | [ML — Data Transformations and Feature Engineering](Part27_ML%20-%20Data%20Transformations%20and%20Feature%20Engineering.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part27_ML%20-%20Data%20Transformations%20and%20Feature%20Engineering.ipynb) |

### Part 9 — Machine Learning: Regression

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part28 | [Linear Regression Example](Part28_Linear%20Regression%20Example.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part28_Linear%20Regression%20Example.ipynb) |
| Part29 | [Linear Regression Code Along — Ecommerce Customers](Part29_Linear%20Regression%20Code%20Along.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part29_Linear%20Regression%20Code%20Along.ipynb) |
| Part30 | [Linear Regression Consulting Project — Cruise Ships](Part30_Linear%20Regression%20Consulting%20Project.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part30_Linear%20Regression%20Consulting%20Project.ipynb) |
| Part31 | [Linear Regression Consulting Project — SOLUTIONS](Part31_Linear%20Regression%20Consulting%20Project%20-%20SOLUTIONS.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part31_Linear%20Regression%20Consulting%20Project%20-%20SOLUTIONS.ipynb) |
| Part32 | [Logistic Regression Example](Part32_Logistic%20Regression%20Example.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part32_Logistic%20Regression%20Example.ipynb) |
| Part33 | [Titanic Logistic Regression Code Along](Part33_Titanic%20Logistic%20Regression%20Code%20Along.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part33_Titanic%20Logistic%20Regression%20Code%20Along.ipynb) |
| Part34 | [Logistic Regression Consulting Project — Customer Churn](Part34_Logistic%20Regression%20Consulting%20Project.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part34_Logistic%20Regression%20Consulting%20Project.ipynb) |
| Part35 | [Logistic Regression Consulting Project — SOLUTIONS](Part35_Logistic%20Regression%20Consulting%20Project%20-%20SOLUTIONS.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part35_Logistic%20Regression%20Consulting%20Project%20-%20SOLUTIONS.ipynb) |

### Part 10 — Machine Learning: Tree Methods

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part36 | [Tree Methods Doc Example — Random Forest & GBT](Part36_Tree%20Methods%20Doc%20Example.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part36_Tree%20Methods%20Doc%20Example.ipynb) |
| Part37 | [Tree Methods Code Along](Part37_Tree%20Methods%20Code%20Along.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part37_Tree%20Methods%20Code%20Along.ipynb) |
| Part38 | [Tree Methods Consulting Project — Dog Food Spoilage](Part38_Tree%20Methods%20Consulting%20Project.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part38_Tree%20Methods%20Consulting%20Project.ipynb) |
| Part39 | [Tree Methods Consulting Project — SOLUTION](Part39_Tree%20Methods%20Consulting%20Project%20-%20SOLUTION.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part39_Tree%20Methods%20Consulting%20Project%20-%20SOLUTION.ipynb) |

### Part 11 — Machine Learning: Clustering

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part40 | [Clustering Code Example — K-Means](Part40_Clustering%20Code%20Example.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part40_Clustering%20Code%20Example.ipynb) |
| Part41 | [Clustering Code Along](Part41_Clustering%20Code%20Along.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part41_Clustering%20Code%20Along.ipynb) |
| Part42 | [Clustering Consulting Project — Hacking Detection](Part42_Clustering%20Consulting%20Project.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part42_Clustering%20Consulting%20Project.ipynb) |
| Part43 | [Clustering Consulting Project — SOLUTIONS](Part43_Clustering%20Consulting%20Project%20-%20SOLUTIONS.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part43_Clustering%20Consulting%20Project%20-%20SOLUTIONS.ipynb) |

### Part 12 — Natural Language Processing

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part44 | [NLP — Tools and Feature Engineering (TF-IDF, NGrams, CountVectorizer)](Part44_NLP%20-%20Tools%20and%20Feature%20Engineering.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part44_NLP%20-%20Tools%20and%20Feature%20Engineering.ipynb) |
| Part45 | [NLP Code Along — SMS Spam Detection](Part45_NLP%20Code%20Along.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part45_NLP%20Code%20Along.ipynb) |

### Part 13 — Recommender Systems

| # | Notebook | Open in Colab |
| --- | ---------- | --------------- |
| Part46 | [Recommender Systems Code Along — ALS / MovieLens](Part46_Recommender%20Systems%20Code%20Along.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part46_Recommender%20Systems%20Code%20Along.ipynb) |
| Part47 | [Recommender Systems Consulting Project — Meal Recommendations](Part47_Recommender%20Systems%20Consulting%20Project.ipynb) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO/blob/main/Pyspark/Part47_Recommender%20Systems%20Consulting%20Project.ipynb) |

---

## Datasets (`datasets/`)

| File | Used In | Description |
| ------ | --------- | ------------- |
| `Ecommerce_Customers.csv` | Part29 | Customer session & spending data |
| `cruise_ship_info.csv` | Part30, Part31 | 158 cruise ships — crew size prediction |
| `fake_customers.csv` | Part27 | Synthetic customer data |
| `sample_linear_regression_data.txt` | Part28 | LibSVM format regression data |
| `customer_churn.csv` | Part34, Part35 | Binary classification — churn prediction |
| `new_customers.csv` | Part34, Part35 | Unlabeled customers for predictions |
| `titanic.csv` | Part33 | Titanic passenger survival data |
| `sample_libsvm_data.txt` | Part32, Part36 | LibSVM format binary classification |
| `College.csv` | Part37 | College data for tree methods |
| `dog_food.csv` | Part38, Part39 | Dog food spoilage feature importance |
| `hack_data.csv` | Part42, Part43 | Hacking incident clustering data |
| `seeds_dataset.csv` | Part41 | Seeds morphology — K-Means |
| `sample_kmeans_data.txt` | Part40 | LibSVM format clustering data |
| `SMSSpamCollection` | Part45 | SMS spam/ham classification dataset |
| `movielens_ratings.csv` | Part46 | MovieLens user-movie ratings |
| `Meal_Info.csv` | Part47 | Meal recommendation data |

> **Missing datasets** (not in repo): `APPL_stock.csv`, `walmart_stock.csv`, `sales_info.csv`, `ContainsNull.csv`, `people.json` (Part13–Part16, Part23–Part24), `billing_data.csv`, `airport-codes-na.txt`, `departuredelays.csv` (Part08).

## `lib/` — JAR Files

Required for Part26 (BigQuery Connection):

- `spark-3.5-bigquery-0.37.0.jar`
- `spark-bigquery-with-dependencies_2.12-0.37.0.jar`
