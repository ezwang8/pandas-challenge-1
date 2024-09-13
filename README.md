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

3. **Install Jupyter Notebook:**
   If Jupyter is not already installed, you can install it with Python by running:

   ```bash
   pip install jupyter
   ```
   
4. **Install required pandas packages:**
   You can install the necessary package by running:

   ```bash
   pip install pandas
   ```

6. **In Python, navigate to the Project Directory:**
   ```bash
   cd wholesale_data_analysis
   ```

7. **Launch Jupyter Notebook:**
   To open the `.ipynb` file, launch Jupyter Notebook by running:

   ```bash
   jupyter notebook
   ```

   This will open the Jupyter Notebook interface in your default web browser.

8. **Open the Notebook:**
   In the Jupyter interface, navigate to the `wholesale_data_analysis.ipynb` file and click on it to open. Once opened, you can run the cells within the notebook to execute the analysis.

## File Roles
- **wholesale_data_analysis.ipynb:** The main script that runs the program. It contains the full data analysis process for exploration, transformation, and validation of the dataset.
- **client_dataset.csv:** The CSV file that contains the raw dataset used for analysis. It has a variety of data separated into columns. Including client information, order details, product categories, and quantities.

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
