# Data Analytics Project - Human Resource Data

This project is a data analytics project that involves analyzing Human Resource data for a brand. The project utilizes MySQL and PowerBI for data processing, cleaning, exploratory data analysis (EDA), and visualization.

## Project Overview

The goal of this project is to analyze and gain insights from the Human Resource data of a brand. The data is initially loaded from a CSV file into a MySQL database. SQL queries are then used to clean the data and perform exploratory data analysis. Finally, the result sets obtained from the SQL queries are visualized using PowerBI.

## Project Workflow

The project follows the following workflow:

1. **Data Loading**: The Human Resource data is loaded from a CSV file into a MySQL database. This step involves creating the necessary tables and importing the data.

2. **Data Cleaning**: SQL queries are used to clean the data and ensure data integrity. This step involves handling missing values, removing duplicates, correcting inconsistent data, and transforming data if necessary.

3. **Exploratory Data Analysis (EDA)**: SQL queries are utilized to perform exploratory data analysis on the Human Resource data. Various queries can be executed to extract meaningful insights and answer specific questions about the data.

4. **Data Visualization**: The result sets obtained from the SQL queries are imported into PowerBI for visualization purposes. PowerBI provides a rich set of tools and visualizations to create interactive and insightful dashboards.

## Repository Structure

The repository contains the following files:

- `data.csv`: The original Human Resource data in CSV format.
- `schema.sql`: SQL script containing the table schema for creating the MySQL database tables.
- `data_load.sql`: SQL script for loading the data from the CSV file into the MySQL database.
- `data_cleaning.sql`: SQL script for performing data cleaning operations.
- `eda.sql`: SQL script for executing exploratory data analysis queries.
- `visualization.pbix`: PowerBI file containing the visualizations created from the result sets.

## Requirements

To run this project, you need to have the following software installed:

- MySQL: Used for creating and managing the database.
- PowerBI: Used for data visualization.

## Getting Started

To get started with this project, follow these steps:

1. Install MySQL and PowerBI on your machine.

2. Clone this repository to your local machine or download the project files.

3. Create a MySQL database using the `schema.sql` script.

4. Load the Human Resource data into the MySQL database using the `data_load.sql` script.

5. Execute the `data_cleaning.sql` script to perform data cleaning operations.

6. Run the `eda.sql` script to execute exploratory data analysis queries and obtain result sets.

7. Open PowerBI and import the result sets obtained from the SQL queries.

8. Use PowerBI to create visualizations and dashboards based on the data.

## Conclusion

By utilizing MySQL for data processing and PowerBI for visualization, this data analytics project provides valuable insights into the Human Resource data for a brand. The project demonstrates the effectiveness of SQL queries and PowerBI in analyzing and presenting data in a meaningful way.
