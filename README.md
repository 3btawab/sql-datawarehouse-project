# sql-datawarehouse-project
building a modern data warehouse by using sql 

📊 SQL Data Warehouse Project
📌 Project Overview

This project demonstrates building a Data Warehouse using SQL following a 3-layer architecture approach.

The goal of this project is to simulate a real-world data engineering workflow including:

Data extraction

Data transformation

Data modeling

Analytical reporting

🏗 Architecture

The project follows a 3-Layer Data Warehouse Architecture:

1️⃣ Bronze Layer (Raw Data Layer)

Stores raw data as received from source systems

No transformations applied

Used for traceability and recovery

2️⃣ Silver Layer (Cleaned & Transformed Layer)

Data cleaning (NULL handling, formatting)

Data type corrections

Basic transformations

Deduplication

3️⃣ Gold Layer (Business Layer)

Star Schema design

Fact and Dimension tables

Optimized for analytics and reporting