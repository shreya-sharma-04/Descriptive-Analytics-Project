## Amazon Product Analysis Dashboard

📌 Project Overview

The Amazon Product Analysis Dashboard is an interactive data visualization project designed to analyze Amazon product data, evaluate pricing and discount strategies, and understand product distribution across different categories.

The dashboard provides a consolidated view of product counts, actual prices, discounted prices, ratings, and discount percentages. It helps users identify popular product categories, compare pricing patterns, and explore relationships between discounts and customer ratings.

🎯 Project Objectives
Analyze the distribution of products across Amazon categories.
Compare actual prices with discounted prices.
Evaluate product discounts and pricing trends.
Examine customer ratings across different discount percentages.
Identify product categories with the highest number of listings.
Provide actionable insights to support pricing and product decisions.
📊 Dashboard Features
1. Interactive Category Filter

A category slicer allows users to filter the dashboard by product category and subcategory, making it easier to analyze specific product segments.

2. Key Performance Indicators (KPIs)

The dashboard displays four key metrics:

KPI	Displayed Value	Description
Total Products	1K	Approximate number of products analyzed
Sum of Discounted Price	6M	Aggregate discounted price value
Sum of Rating	6.00K	Aggregate of the rating field
Sum of Actual Price	9M	Aggregate actual price value

Note: Values are shown in the abbreviated format displayed on the dashboard. Totals may change when filters are applied.

3. Top 10 Product Categories by Product Count

A horizontal bar chart ranks product categories by the number of products listed. It helps identify categories with the largest product representation.

4. Product Distribution by Category

A doughnut chart visualizes the distribution of products among major categories and subcategories. It makes it easier to compare category shares and identify dominant segments.

5. Actual Price vs. Discounted Price by Category

A clustered column chart compares average actual prices and average discounted prices across product categories. This visualization helps evaluate pricing differences and potential savings.

6. Discount Percentage vs. Customer Rating

A scatter plot explores the relationship between product discount percentages and customer ratings. It helps identify patterns, clusters, and potential outliers in the data.

🔍 Key Insights

Based on the dashboard's displayed visualizations:

Category concentration: Some categories have more product listings than others, indicating an uneven distribution of products.
Pricing differences: Actual prices are generally higher than discounted prices across the displayed categories.
Discount variation: Products have varying discount percentages, creating opportunities to compare promotional strategies.
Rating distribution: Customer ratings vary across the observed discount percentages, and the relationship may not be linear.
Category-level comparison: Filtering by category enables more focused analysis of pricing, product counts, and ratings.

These are preliminary observations from the dashboard; further analysis of the underlying dataset is required to confirm statistical relationships and business conclusions.

🛠️ Tools and Technologies

The dashboard screenshot shows an interactive analytical interface. Update this section to reflect the tools used in your project.

Data Source: Amazon product dataset
Data Analysis: Data cleaning, transformation, and aggregation
Visualization: Dashboard charts, KPI cards, slicers, and interactive filters
Potential Tools: Microsoft Power BI, Microsoft Excel, Python, or another BI platform, depending on your implementation
📁 Project Structure

A suggested repository structure is:

Amazon-Product-Analysis/
│
├── README.md
├── data/
│   └── amazon_products.csv
├── dashboard/
│   └── amazon_dashboard_file
├── images/
│   └── dashboard_screenshot.png
└── documentation/
    └── data_dictionary.md


Adjust the filenames and folders to match your actual project files.

🚀 How to Use the Dashboard
Open the dashboard in the relevant visualization software.
Use the Main Category filter to select a category or subcategory.
Review the KPI cards to understand the selected data.
Explore the top 10 categories chart to compare product counts.
Compare actual and discounted prices across categories.
Examine the doughnut chart to understand product distribution.
Use the scatter plot to explore discount percentages and customer ratings.
Clear or change filters to compare different product segments.
💼 Business Applications

This dashboard can support:

Pricing strategy: Compare actual and discounted prices across categories.
Product assortment planning: Identify categories with higher product representation.
Promotional analysis: Examine discount patterns across products.
Customer review analysis: Explore rating distributions alongside discount levels.
Market research: Understand how product listings and prices vary across categories.
⚠️ Limitations and Considerations
Product counts depend on the completeness and quality of the source dataset.
The sum of ratings is not equivalent to an average customer rating.
A relationship between discount percentage and rating does not establish causation.
Category labels and aggregated values should be validated against the underlying data.
Dashboard figures may change based on active filters.
🔮 Future Improvements
Add average rating and average discount KPIs.
Include a calculated savings percentage based on actual and discounted prices.
Add price distribution and rating distribution charts.
Identify top-rated and most-discounted products.
Introduce brand-level and product-level comparisons.
Add data validation and automated refresh capabilities.
📌 Conclusion

The Amazon Product Analysis Dashboard provides a visual approach to understanding product distribution, pricing differences, discounts, and customer ratings. By combining KPI cards, category filters, bar charts, a doughnut chart, and a scatter plot, it makes product data easier to explore and compare.

The project demonstrates practical applications of data analysis and visualization for e-commerce insights and data-driven decision-making.

Project: Amazon Product Analysis Dashboard
Domain: E-commerce Analytics
Purpose: Product, pricing, discount, and rating analysis
Author: **Shreya Sharma**
