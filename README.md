# E-Commerce Data Analysis Project

## Overview
This project focuses on analyzing a fictional e-commerce dataset using Python's Pandas library. The objective is to explore and transform the data to derive meaningful insights, such as identifying top clients and calculating profits.

## Features
- **Data Exploration:** Exploring the dataset to identify key features and answer specific business questions.
- **Data Transformation:** Creating columns for subtotals, shipping costs, total prices, costs, and profits.
- **Data Validation:** Verifying the calculations using provided order receipts.
- **Data Summarization:** Summarizing the top 5 clients by total revenue and profits.

## Files
- **wholesale_data_analysis_starter_code.ipynb:** Jupyter notebook containing the full data analysis process, including exploration, transformation, and validation of the data.
- **client_dataset.csv:** CSV file containing the raw dataset used for analysis. This includes columns such as client information, order details, product categories, and quantities, which are used to calculate profits and revenue.

## Requirements
- Python 3.8+
- Pandas
- Jupyter Notebook

## Steps
1. **Explore the Data:** Understand the structure of the dataset and identify key features such as the top clients and most popular item categories.
2. **Transform the Data:** Perform calculations to create new columns that capture the subtotals, shipping costs, total prices, costs, and profits for each line item.
3. **Confirm Results:** Validate the transformed data against provided order receipts to ensure the calculations are accurate.
4. **Summarize and Analyze:** Create a summary DataFrame showing the total units purchased, shipping costs, total revenue, and total profit for the top 5 clients. Sort the data by total profits in descending order.

## Summary of Findings
The top client by total profit was **Client 24741**, generating **$36.58 million** in profit, followed by **Client 38378** and **Client 66037** with profits of **$3.27 million** and **$3.25 million**, respectively. A small number of clients contribute significantly to the company’s overall revenue.

## Usage
- Run the Jupyter notebook `wholesale_data_analysis_starter_code.ipynb` to perform the analysis.
- Use the `client_dataset.csv` file as the data source for the analysis.
