# Superstore-Sales-Analysis
This project presents a comprehensive analysis of the Superstore dataset using Python, Excel, and Power BI to identify trends, patterns, and key insights to drive business decisions.

## Project Duration
Start Date: 06-23-2025
End Date: 06-26-2025

## Project Structure
Superstore-Sales-Analysis/<br>
├── data/                        # Original dataset<br>
├── excel_analysis/             # Initial analysis using Excel<br>
├── images/                     # Charts generated from analysis<br>
├── powerbi_dashboard/          # Power BI dashboard file<br>
├── python_analysis/            # Jupyter Notebook with Python code

## Tools Used
- Excel for basic pivot analysis
- Python(Pandas, Matplotlib, Seaborn) for EDA
- Power BI for dynamic dashboards and business reporting

## Key Insights
- Sales Trend: Clear seasonal spikes, especially in Q4 of each year. Strategic planning should focus on this peak.
- Top Categories: Technology is the most profitable category. Office Supplies and Furniture also contribute significantly.
- Discount Patterns: High discounts reduce overall profitability. Tables in Furniture are especially unprofitable.
- Top Products: A few products dominate sales—ensure consistent stock and marketing focus on them.
- Regional Sales: West and East regions are strongest. Central and South show potential for targeted growth.
- Shipping Impact: Standard Class leads in volume. Same Day delivery negatively impacts profit margins.
- California Performance: California stands out as the highest sales-generating state, with strong performance across all product categories. It significantly contributes to both revenue and profit, making it a strategic region for targeted campaigns and inventory optimization.


## Final Report Summary

### 1. Data Cleaning
- Converted Order Date and Ship Date to date
- Removed duplicates and handled nulls
- Converted Sales, Profit, Qunatity and Disocunt to numeric types with decimals
- Renamed Row ID column to ID
- Corrected date formatting and handled wrongly entered values
- Checked logical consistency between Order Date and Ship Date and changed the dates od shipped date correctly
- Highlighted negative Profit values in red for easy identification
- Highlighted Sales values exceeding $10,000 in yellow

### 2. Descriptive Stats
- Analyzed key metrics like Sales, Quantity, Profit and Discount to understand central tendencies, spread and anomalies
- Observed that profit values vary widely, with several negative values impacting overall profitability
- Found that most discounts fall between 0% and 30%, with 20% being the most frequent
- Identified patterns among 793 unique customers and 1,850 unique products, showing a wide and diverse customer base
- Categorized data into 3 main categories (Furniture, Office Supplies, Technology) and 17 sub-categories, enabling detailed performance analysis

### 3. Time Series Analysis
- Extracted year-wise trends showing growth in total orders from 2014 to 2017
- Sales consistently rise toward the end of each year, with noticeable peaks in the final months—suggesting seasonal demand, likely around November and December
- Found some entries in 2018—likely data spillover or incorrect entries, which were reviewed for quality

### 4. Visual Highlights
- Monthly sales trend
- Profit by category and sub-category
- Sales by region and shipping mode
- Top 10 products by sales

### 5. Power BI Dashboard
Interactable dashboard showing:
- Segment-wise performance
- Regional heatmaps
- Discount vs Profit analysis

## Next Steps
- Recommend predictive modeling (forecasting future sales)
- Drill deeper into customer loyalty and segmentation
- Automate reporting with updated datasets monthly

## How to Use
- Open the Excel/Power BI files from their respective folders
- Launch the Jupyter Notebook (python_analysis.ipynb) in JupyterLab/VS Code
- Check /images/ folder for generated charts

## Author

Dhyuthi Sri Ramya Cheruvu <br>
Data Analyst Enthusiast
