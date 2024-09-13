# E-Commerce Data Analysis

## Project Overview
This program is tasked to analyze the e-commerce's company data with Python's Pandas library. Users will be able to explore and transform the dataset to gather valuable information for the company, such as indentifying the top clients and calculating how much profit each had generated.

## Installation Instructions
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ezwang8/pandas-challenge-1.git
   ```
2. **Check to make sure Python is installed on your system.**
   Open your system's terminal and type the following command:

   ```bash
   python --version
   ```

   Depending on the system, use instead:

   ```bash
   python3 --version
   ```

   The command will display `Python 3.x.x` if Python 3.x is installed. If not, you can download it in the website: [python.org](https://www.python.org/downloads/).

3. **Navigate to the Project Directory:**
   ```bash
   cd wholesale_data_analysis
   ```
4. **Run the Python Script:**
   Run the script, in your system's installed Python application, with:
   ```bash
   python wholesale_data_analysis.ipynb
   ```

## File Roles
- **wholesale_data_analysis.ipynb:** The main script that runs the program. It contains the full data analysis process for exploration, transformation, and validation of the dataset.
- **client_dataset.csv:** The CSV file that contains the raw dataset used for analysis. It has a variety of data separated into columns. Including client information, order details, product categories, and quantities.
























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
