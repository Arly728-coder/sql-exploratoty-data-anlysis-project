# sql-exploratory-data-anlysis-project  📊

Welcome to the SQL Exploratory Data Analyst Portfolio Project repository! This project demonstrates a hands-on, end-to-end exploratory data analysis (EDA) framework using SQL, mirroring real-world data analytics workflows.

🛠️ Project Overview
As data analysts, exploring new datasets and databases is a fundamental routine. This project follows a structured methodology to ask the right questions, uncover insights, and solve business problems using basic and intermediate SQL skills.

The project covers database exploration, dimension profiling, date-range analysis, business metrics aggregation, magnitude analysis, and ranking techniques.

🗺️ Project Roadmap
The workflow is broken down into the following key phases:

1  Database Exploration: Inspecting database schemas, objects, and metadata tables to understand structure and table columns.

2  Dimension Exploration: Identifying unique values, categories, and understanding data granularity across dimensions.

3  Date Range Exploration: Finding boundaries (earliest and latest dates) to determine time spans and calculate customer age metrics.

4  Measure Exploration: Calculating key performance indicators (KPIs) and business Big Numbers using aggregate functions (SUM, AVG, COUNT).

5  Magnitude Analysis: Comparing measure values across different dimensions (e.g., total sales by country, revenue by category) to find top and bottom performers.

6  Ranking Analysis: Identifying top and bottom performers using TOP clauses and window functions (ROW_NUMBER()).

📂 Repository Structure
Plaintext
├── datasets/            # Raw CSV data files used for the project
├── docs/                # Project documentation and resources
└── scripts/             # SQL scripts for database setup and analysis
    ├── 01_database_exploration.sql
    ├── 02_dimensions_exploration.sql
    ├── 03_date_range_exploration.sql
    ├── 04_measures_exploration.sql
    ├── 05_magnitude_analysis.sql
    ├── 06_ranking_analysis.sql
    └── ...
🚀 Getting Started & Database Setup
If you need to set up the database and run the scripts locally in SQL Server, you can use the initialization scripts provided in the scripts/ folder:

1  Run the Initialization Script: Open 01_database_exploration.sql or the database initialization script in SQL Server Management Studio (SSMS), update the file paths if necessary, and execute it to create the database schema and insert sample data.

2  Alternative Methods: You can also import CSV files using the flat-file import wizard or restore the provided database backup file (.bak).

💡 Key SQL Techniques Used

Metadata Queries: Querying INFORMATION_SCHEMA tables to inspect database architecture.

Aggregations: Using SUM(), AVG(), and COUNT() with DISTINCT to ensure accurate metrics.

Conditional Grouping: Utilizing GROUP BY and ORDER BY clauses to analyze metrics across dimensions.

Window Functions: Employing ranking functions for advanced reporting flexibility.

👤 Author
Data with Baraa (Portfolio Project guided workflow)

Implemented by [Arsalan posha]

If you found this project helpful or inspiring, feel free to give it a ⭐ on GitHub!
