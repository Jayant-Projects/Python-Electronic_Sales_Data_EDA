# Exploratory Data Analysis (EDA) of Electronics Store Sales Data

In this project, I conducted an in-depth Exploratory Data Analysis (EDA) using Python's Pandas and Matplotlib libraries. The dataset under investigation comprises 12 months' worth of sales data from an electronics store, providing a wealth of information including purchase details categorized by month, product type, cost, purchase address, and more.

## Getting Started

To kick off the project, I imported essential libraries such as pandas, matplotlib, os, and glob. The initial phase primarily focused on data cleaning, which included tasks like:

1. Removing rows with missing values (NaN) from the DataFrame.
2. Filtering and dropping rows based on specific conditions.
3. Changing the data types of columns using methods such as `to_numeric`, `to_datetime`, and `astype`.

## Data Exploration

Once the data was cleaned and prepared, I transitioned into the data exploration phase. In this phase, I aimed to address five high-level business questions:

1. **Best Month for Sales:** I determined the best month for sales and calculated the total revenue generated during that month.

2. **Leading City in Sales:** I identified the city that led in product sales.

3. **Optimal Advertisement Timing:** I found the optimal time for displaying advertisements to maximize customer purchases.

4. **Frequently Sold Together Products:** I discovered which products were frequently sold together.

5. **Top Selling Product:** I identified the top-selling product and explored the factors contributing to its success.

## Key Techniques Used

To answer these questions and gain valuable insights, I employed a variety of Pandas and Matplotlib functionalities, including:

- **Data Consolidation:** I concatenated multiple CSV files to create a consolidated DataFrame using `pd.concat`.

- **Feature Engineering:** I introduced new columns to enhance data insights.

- **String Manipulation:** I extracted and manipulated strings within cells using the `.str` accessor for better analysis.

- **Custom Data Transformations:** I utilized the `.apply()` method for custom data transformations.

- **Grouping and Aggregation:** I employed the `groupby` operation to perform aggregate analysis.

- **Data Visualization:** I created visually informative bar charts and line graphs to visualize findings.

- **Graph Annotations:** To enhance clarity, I added labels and annotations to the graphs.

This EDA project provides a comprehensive understanding of the electronics store's sales data, answering crucial business questions and offering insights for decision-making. Feel free to explore the Jupyter Notebook in this repository for a detailed step-by-step analysis.

Thank you for visiting my GitHub page, and I hope you find this project informative and valuable.
