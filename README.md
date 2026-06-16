# Book-Analytics-System-ETL-Datawarehouse-and-OLAP



## Project Overview

The Book Analytics System is a Data Warehousing project that demonstrates the complete ETL (Extract, Transform, Load) process, Data Warehouse design, and OLAP-based analytical reporting using book sales and customer data.

The project extracts raw book data, transforms and cleans it, loads it into a structured data warehouse, and performs analytical queries to generate meaningful business insights.

---

## Objectives

* Implement ETL processes for data integration.
* Design a Data Warehouse using dimensional modeling.
* Create Fact and Dimension tables.
* Perform OLAP operations for analytical reporting.
* Generate insights from book-related datasets.

---

## Dataset

The project uses a book dataset containing information such as:

* Book ID
* Title
* Author
* Category
* Publisher
* Sales Information
* Customer Details
* Transaction Records

Dataset files are included in this repository.

---

## Technologies Used

* SQL
* Data Warehousing Concepts
* ETL Process
* OLAP Operations
* Database Management Systems

---

## ETL Process

### Extract

Data is collected from source datasets.

### Transform

* Data cleaning
* Handling missing values
* Data standardization
* Data validation

### Load

Transformed data is loaded into the Data Warehouse for analysis.

---

## Data Warehouse Design

### Dimension Tables

* DimBook
* DimAuthor
* DimCategory
* DimCustomer
* DimDate

### Fact Table

* FactSales

The warehouse follows a Star Schema design for efficient analytical processing. Data warehouses commonly use dimensional models such as star schemas to support analytical queries.

---

## OLAP Analysis

The project supports multidimensional analysis including:

* Sales by Category
* Sales by Author
* Sales by Publisher
* Monthly Sales Trends
* Customer Purchase Analysis

OLAP enables analytical processing and aggregation across multiple dimensions.

---

## Features

* End-to-end ETL pipeline
* Data Warehouse implementation
* Star Schema modeling
* Analytical SQL queries
* Business intelligence reporting

---

## Project Structure

```text
Book-Analytics-System-ETL-Datawarehouse-and-OLAP/
│
├── Dataset/
├── ETL Scripts/
├── SQL Queries/
├── Data Warehouse Design/
├── OLAP Analysis/
└── README.md
```

---

## Learning Outcomes

Through this project, I gained practical experience in:

* ETL Pipeline Development
* Data Cleaning and Transformation
* Data Warehouse Design
* Star Schema Modeling
* OLAP Operations
* SQL-Based Analytics

---

## Author

Harini Perumal

GitHub: https://github.com/HARINI-029
