# Vrinda_store_data_analysis-Interactive-dashboards-using-Excel-
## Objective:
Vrinda Stores aims to create an annual sales report for 2022, enabling them to gain insights into their customers and drive sales growth in 2023.
# Dataset Used:
# Data Cleaning:
Several steps were taken to clean the data:
1) Each column was thoroughly examined to ensure data cleanliness.
2) Duplicate or null values in the data were identified and addressed.
3) Data consistency was checked, revealing inconsistencies in the Gender column. Men were represented as both 'M' and 'Men', while Women were represented as both 'Women' and 'W'.

# Solutions:
To rectify the inconsistencies:
i) All instances of 'Men' and 'Men' were replaced with 'M'.
ii) Similar steps were taken for other columns by identifying and correcting any inconsistent data.

# Data Processing:
The following data processing steps were implemented:
1) An age group categorization was created using a formula to represent different age categories.
   =IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))
2) The month was extracted from the date column using the formula:
   =TEXT(G2,"mmmm")

# Data Analysis:
The data analysis phase involved:
1) Creating pivot tables to answer specific questions.
2) Merging all pivot tables into one dashboard and incorporating slicers to make the dashboard interactive and dynamic.

# Dashboards:
 
# Project Insights:
The following insights were derived from the dashboards:
• Women customers have a higher likelihood of purchasing products compared to men, accounting for approximately 65% of total sales.
• The top three states with the highest product purchases are Maharashtra, Karnataka, and Uttar Pradesh.
• The adult age group (30-49 years) makes the most significant contribution, representing approximately 50% of total sales.
• The majority of customers place their orders through Amazon, Flipkart, and Myntra channels.

# Final Conclusion:
To enhance sales at Vrinda Stores, targeted efforts should focus on women customers within the age group of 30-49 years residing in Maharashtra, Karnataka, and Uttar Pradesh. Promotions such as ads, offers, and coupons should be prominently featured on Amazon, Flipkart, and Myntra platforms to effectively reach and engage this target audience.
