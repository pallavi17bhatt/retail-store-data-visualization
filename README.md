# Retail store Data Visualization and Analysis
This project is a data visualization and analysis project for a retail store. The data is from a retail store that sells various products. The data contains information about the products, customers, and transactions. The goal of this project is to analyze the data and create visualizations to help the retail store understand their business better.

## Data Input files
* In `./data/` folder, Online_Retail_full_copy.csv

## How to setup 
* Install python version 3.11.4 and pip
* Install requirements.txt, Run the following command in the project root directory
```pip install -r requirements.txt```

* This project requires the following specific dependency versions,
```
pandas==1.5.3
matplotlib==3.6.2
numpy==1.23.5
```

## How to run 
```python3 retail_data_viz.py```

## Output Details 
The output of this project is a set of visualizations and intermediate csv files that provide insights into the retail store's business. 
* Output Directory : `./output/`

This includes:

CSVs
* df_cleaned_UK.csv
* product_analysis.csv
* high_value_customer_sales.csv
* product_analysis_high_value_customer.csv
* stockcode_quantity_description_table.csv

Visualizations:
* Total_Revenue_by_Average_Selling_Price_Product_Category.svg
* Total_Quantity_Sold_by_Average_Selling_Price_Product_Category.svg
* Total_Revenue_and_Quantity_by_Average_Selling_Price_Category.svg
* Top_5_Products_by_Revenue.svg
* Top_5_Selling_Products_by_Quantity.svg
* Monthly_Quantity_Sold_Trend_per_Price_Category.svg
* Monthly_Revenue_Trend_per_Price_Category.svg
* Revenue_by_Average_Selling_Price_Product_Category_High_Value_vs_Other_Customers.svg
* Total_Quantity_Sold_by_Average_Selling_Price_Product_Category_High_Value_vs_Other_Customers.svg
* Comparison_Top_5_Selling_Products_by_Quantity_sold_across_Customer_Segment.svg
* Comparison_Top_5_Products_by_Revenue_they_generate_across_Customer_Segment.svg
* Pie_Revenue_Contribution_High_Value_vs_Other_Customers.svg


