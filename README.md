# Data Analytics Project

## Overview
This project analyzes sales data from `SalesData.xlsx` to uncover insights into sales performance, product line trends, deal size contributions, and overall business patterns. The analysis includes data visualization and statistical computations to support decision-making.

## Data Source
The dataset contains key business information such as:
- **ORDERNUMBER**: Unique sales order identifier
- **QUANTITYORDERED**: Number of units ordered
- **PRICEEACH**: Price per unit
- **ORDERDATE**: Date of order placement
- **STATUS**: Order status (Shipped, Cancelled, On Hold, etc.)
- **PRODUCTLINE**: Category of the product
- **PRODUCTCODE**: Unique product identifier
- **CUSTOMERNAME**: Customer who placed the order
- **CITY**: Customer location
- **DEALSIZE**: Classification of the deal (Small, Medium, Large)

## Key Analyses & Insights
1. **Sales Performance Over Time**
   - Trend analysis of total sales over months/years to detect patterns.
   - Identifies seasonality, growth trends, and anomalies.

2. **Best and Worst Performing Product Lines**
   - Determines the highest and lowest sales product lines.
   - Visualized using bar charts for easy comparison.

3. **Deal Size Impact on Sales**
   - Measures correlation between deal size (Small, Medium, Large) and total revenue.
   - Displays percentage contribution of each deal size using pie charts.

4. **Customer Purchase Behavior**
   - Identifies which cities/customers contribute most to revenue.
   - Determines the frequency of orders from repeat customers.

## Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn) for data processing & visualization
- **Jupyter Notebook** for exploratory data analysis
- **Excel** for raw data storage & manipulation

## How to Run the Analysis
1. Install required dependencies:
   ```bash
   pip install pandas matplotlib seaborn openpyxl
   ```
2. Place `SalesData.xlsx` in the project directory.
3. Run the analysis script in a Jupyter Notebook or Python environment.

## Visualizations
- **Line Chart**: Sales trends over time.
- **Bar Chart**: Comparison of sales by product line.
- **Pie Chart**: Contribution of deal sizes to total revenue.

## Conclusion
This project provides valuable insights into sales trends, customer behavior, and business growth opportunities. The visualizations make complex data easier to understand and drive data-driven decision-making.

---

