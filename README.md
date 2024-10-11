Sales Data Analysis

This repository contains a Jupyter notebook for analyzing sales data to identify common product pairs frequently ordered together. 
The analysis includes data preprocessing, grouping products by order, and counting the frequency of product combinations.

Project Overview

The main goals of this project are:
- To clean and preprocess the sales data.
- To identify orders with multiple products.
- To find the most frequently ordered product combinations.
- To visualize the top product pairs using a bar chart.

Files

- Sales_Data_Analysis.ipynb: Jupyter notebook containing the code for sales data analysis.

Dataset

The dataset is assumed to have the following columns:
- Order ID: Unique identifier for each order.
- Product: Name of the product ordered.
- Quantity Ordered: The quantity of the product in the order.
- Price Each: Price per unit of the product.
- Order Date: Date and time when the order was placed.
- Purchase Address: Address where the order was shipped.

Additional columns may be derived from the dataset for analysis, such as Month, Sales, City, etc.

Analysis Steps

1. Data Cleaning:
   - Remove missing or invalid entries.
   - Convert data types as needed.

2. Identifying Multi-Product Orders:
   - Filter orders with multiple products using the Order ID.

3. Grouping Products by Order:
   - Aggregate the products purchased in the same order.

4. Counting Product Combinations:
   - Use the itertools.combinations and collections.Counter to count occurrences of product pairs.

5. Visualization:
   - Plot a bar chart to display the top 10 most commonly ordered product pairs.

Installation

To run the notebook, you'll need to have Python installed along with the following libraries:
- pandas
- matplotlib
- itertools (built-in)
- collections (built-in)

You can install the required libraries using:
pip install pandas matplotlib


Contributing

Contributions are welcome! If you have suggestions for improving the analysis or adding new features, please open an issue or submit a pull request.

