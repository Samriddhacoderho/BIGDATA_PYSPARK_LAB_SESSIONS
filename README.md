# BIGDATA_PYSPARK_LAB_SESSIONS

## Overview

This repository contains a series of practical lab sessions and data preprocessing exercises centered on Big Data analytics using PySpark. These materials are designed for students and professionals who wish to gain hands-on experience with distributed computing, large-scale data manipulation, and analytical workflows in Apache Spark via the Python interface.

The repository exclusively uses Jupyter Notebooks, offering interactive examples, solutions to common data engineering tasks, and thorough explanations that make it accessible for both beginner and intermediate users.

## Contents

- **data-preprocessing-for-students.ipynb**  
  End-to-end student data preprocessing workflow: schema inference, custom schema definition, null value handling, feature engineering, column manipulation, and statistical summaries using PySpark DataFrames.

- **data-preprocessing-using-pyspark.ipynb**  
  Comprehensive guide to structural and statistical data preprocessing including loading CSV files with custom schemas, identifying and filling nulls, column operations (selection, renaming, deletion), new feature creation, and exporting results using Spark DataFrames.

- **lab-session1.ipynb**  
  Introduction to RDD (Resilient Distributed Dataset) operations in PySpark such as mapping, filtering, partitioning, and basic distributed transformations, providing foundational knowledge for distributed data computation.

- **lab-session2.ipynb**  
  Hands-on practice implementing the classic word count problem in PySpark using RDD transformations and actions, demonstrating distributed text processing.

- **lab-session3.ipynb**  
  Advanced lab focusing on RDD manipulation with additional tasks such as file I/O, data parsing, filtering, aggregation, custom function application, and persistence using Spark RDD APIs.

- **datasets**  
  Example CSV files (such as `students_data-*.csv`, `employees-*.csv`) for use in the practical exercises, included for reproducibility and further experimentation.

## Features

- **Comprehensive Notebooks**: Each notebook is self-contained with descriptive markdown cells and detailed code explanations.
- **Realistic Datasets**: Sample datasets provided for each workflow, enabling authentic, hands-on experimentation.
- **Modern PySpark APIs**: All labs use up-to-date PySpark features and recommended best practices.
- **Reproducibility**: Notebooks are designed for easy replication—simply open in JupyterLab or any compatible environment and run.
- **Practical Scenarios**: Exercises range from introductory to advanced, covering common data engineering and analysis scenarios.

## Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab
- PySpark (>= 3.0)
- pandas, numpy (recommended for data manipulation and inspection)

Installation using pip:
```bash
pip install pyspark pandas jupyter
```

## Getting Started

Clone this repository:
```bash
git clone https://github.com/Samriddhacoderho/BIGDATA_PYSPARK_LAB_SESSIONS.git
cd BIGDATA_PYSPARK_LAB_SESSIONS
```

Start your Jupyter Notebook server:
```bash
jupyter notebook
```

Open any of the `.ipynb` files and follow the instructions in each notebook.

## Learning Outcomes

By working through these materials, you will be able to:
- Set up Spark sessions and work with Spark DataFrames and RDDs
- Load, inspect, and preprocess datasets for analytics
- Address missing values and perform feature engineering
- Execute distributed computations over large data collections
- Persist results and automate data workflows
- Apply best practices and idiomatic patterns in PySpark

## Author

Samriddha Raj Satyal  
*Student ID: 240488*  
Contact: [satyalsamriddha@gmail.com](mailto:satyalsamriddha@gmail.com)
         

---

> For academic, research, and educational use. Please cite or reference if using these materials in your own work.
