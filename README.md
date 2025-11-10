RETAIL STORE DATASET-

Overview -
This project analyzes the Retail Store Dataset, which contains transactional sales data for products across categories like Clothing, Beauty, and Electronics.
The main goal is to extract actionable insights on:
- Sales performance by product category, gender, and age group
- Trends and seasonality between 2023 and 2024
- Total orders, total quantity, and revenue growth
The analysis was performed in Python (for cleaning and exploration) and Power BI (for dashboard visualization).

Dataset Details-
Source - /kaggle/input/retail-store-dataset/Retail Store Dataset.csv
Column	Description
Transaction ID
Customer ID
Date	Unique for each order
Related to each customer
Order date
Product Category	Product type (Clothing, Beauty, Electronics)
Gender	Male / Female
Age Group	Customer’s age group
Quantity	Units sold
Price per Unit	Price of a single product
Total Amount	Quantity × Price per Unit
Year	Extracted from the date for trend comparison (2023, 2024)

Data Cleaning & Preparation-
•	Removed duplicate rows
•	Converted Date column to datetime format
•	Ensured Quantity, Price per Unit, and Total Amount are numeric

Exploratory Data Analysis (EDA)-
 Sales by Product Category-
Category	Total Sales
Clothing	448K
Beauty	444K
Electronics	437K
Clothing generated the highest sales, but all categories performed quite close, suggesting balanced demand.
Sales by Gender
•	Female: ₹677K

•	Male: ₹652K
 Female customers slightly outspent male customers, showing balanced engagement across genders.
 Sales by Age Group
Age Group	Total Amount
26–35	292K
36–45	276K
46–55	269K
56+	267K
18–25	225K
 The 26–35 age group drives the most revenue, making them the core target segment.
 Yearly and Monthly Trends
•	2024 shows consistent or slightly increased performance compared to 2023.
•	Sales spikes appear during festive seasons (August–December).
•	A Power BI slicer allows year comparison interactively.
 Increment and Price Adjustment Analysis
In Power BI, a price adjustment slicer (e.g., +20%) was used to test how pricing changes affect revenue.
 Small increments (5–10%) led to minimal revenue drop, showing stable demand elasticity.

Tools Used
Kaggle – Data cleaning & preprocessing (Pandas, Matplotlib)
Link to Kaggle notebook - https://www.kaggle.com/code/ashmeetsian/retail-store-datset/edit
Power BI – Dashboard creation and KPI visualization
Excel – Initial exploration and pivot summary
Conclusion
This project provided a complete end-to-end retail analytics workflow — from cleaning raw data to building an interactive Power BI dashboard.
The insights derived can help retailers:
- Target the right customer segments
- Optimize pricing and promotions
- Identify strong performing categories
- Plan inventory and marketing around seasonal peaks
