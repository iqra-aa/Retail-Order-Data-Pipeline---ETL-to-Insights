<h1 align="center"> Data Analytics Project Using Python & SQL</h1>

This project presents a complete data analytics workflow using **Python, Pandas, and SQL Server**, based on retail order data. It demonstrates the process of working with raw data, preparing it for analysis, storing it in a database, and extracting useful insights through SQL queries.

<h3>Project Overview</h3>

The goal of this project is to demonstrate a practical end-to-end approach to data analytics. The workflow covers data extraction, data cleaning, transformation, database integration, and analytical querying.

<h3>Project Workflow</h3>

**1. Data Extraction:**
The retail orders dataset is obtained using the Kaggle API.

**2. Data Cleaning and Preprocessing:**
Python and Pandas are used to prepare the dataset by handling missing values, transforming columns, creating calculated fields, and converting data types.

**3. Database Integration:**
The processed dataset is loaded into SQL Server using SQLAlchemy and PyODBC.

**4. Data Analysis:**
SQL queries are used to explore the data, perform aggregations, identify trends, and generate useful business insights.

<h3>Project Architecture</h3>

**Kaggle API:**
Used to retrieve the retail order dataset.

**Python & Pandas:**
Used for data cleaning and transformation, including:

1. Handling missing values
2. Transforming and formatting columns
3. Creating calculated fields
4. Converting data types
5. Preparing data for database storage

**SQL Server:**
Used to store the processed dataset and perform analytical queries.

**SQL Analysis:**
Used to:

1. Analyze sales and order information
2. Identify product and customer trends
3. Examine sales patterns
4. Generate meaningful insights

<h3>Skills Demonstrated</h3>

**Python:**
Used Python and Pandas for data manipulation, cleaning, transformation, and preprocessing.

**SQL:**
Applied SQL for filtering, aggregation, data analysis, and extracting insights.

**ETL:**
Implemented an Extract, Transform, and Load workflow for preparing and moving data into a SQL Server database.

**Data Preparation:**
Worked with raw data to improve its structure and make it suitable for analysis.

**Analytical Thinking:**
Used structured analysis to identify patterns and trends within retail order data.

<h3>How to Run This Project</h3>

### 1. Set Up Python

Make sure Python is installed on your system and create a virtual environment for the project.

### 2. Install Required Libraries

Install the libraries used by the project:

```bash
pip install kaggle pandas sqlalchemy pyodbc
```

### 3. Prepare the Dataset

The repository contains the `orders.csv` dataset used for the analysis.

The Python workflow also includes Kaggle API functionality for downloading the dataset programmatically.

### 4. Run the Data Analysis

The project provides two ways to work with the Python analysis:

**Jupyter Notebook**

```text
Order Data Analysis.ipynb
```

Use the notebook to follow the data cleaning and preprocessing process step by step.

**Python Script**

```text
orders data analysis.py
```

The script provides the Python-based workflow for processing the order data.

### 5. Configure SQL Server

Set up a SQL Server database and load the processed dataset into it.

The Python workflow uses **SQLAlchemy** and **PyODBC** to establish the connection between Python and SQL Server.

### 6. Run SQL Queries

Open:

```text
SQLQuery3.sql
```

in SQL Server Management Studio and execute the queries against the project database.

<h3>Repository Files</h3>

**Order Data Analysis.ipynb**
Notebook containing the data cleaning and preprocessing workflow.

**orders data analysis.py**
Python script for processing the retail order dataset and loading data into SQL Server.

**SQLQuery3.sql**
SQL queries used to analyze the processed data.

**orders.csv**
Retail order dataset used throughout the project.

**project architecture.png**
Diagram illustrating the overall project workflow.

**README.md**
Documentation for the project.

<h3>Key Insights</h3>

**Product Analysis:**
Analyzed product-level revenue and sales performance to understand product contribution.

**Customer Analysis:**
Explored customer purchasing behavior and identified purchasing patterns.

**Sales Trend Analysis:**
Examined sales activity over time to understand temporal patterns.

**Customer Segmentation:**
Analyzed customers based on purchase frequency and order value.

<h3>Project Purpose</h3>

This project demonstrates how different data analytics tools can be combined into a single workflow. Starting with raw retail data, the project moves through data preparation, transformation, database integration, and SQL analysis.

The project provides practical experience with **Python, Pandas, SQL Server, SQLAlchemy, PyODBC, ETL, and data analysis**.

<h3>Author</h3>

**Iqra**

<h3>Let's Connect</h3>

Thank you for exploring this project. Feel free to review the workflow, analysis, and SQL queries, and share any feedback or suggestions.

**Author:** Iqra
