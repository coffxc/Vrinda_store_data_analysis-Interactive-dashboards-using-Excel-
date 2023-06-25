# Vrinda_store_data_analysis(Interactive-dashboards-using-Excel)
## **Project Objective:**
Vrinda Stores aims to create an annual sales report for 2022, enabling them to gain insights into their customers and drive sales growth in 2023.
## **Dataset used:**
[Vrinda store data Analysis](Vrinda_Store Data Analysis.xlsx)

## **Questions to be answered:**
- Compare the sales and orders using single chart.
- Which month got the highest sales and orders?
- Who purchased more - Men or Women?
- What are different order status in 2022?
- List top 10 states contributingto the sales?
- Relation between age and gender based on number of orders.
- Which Channel is contributing maximum to the sales?
- Highest selling category?

## **Data Cleaning:**
Several steps were taken to clean the data:
1) Each column was thoroughly examined to ensure data cleanliness.
2) Duplicate or null values in the data were identified and addressed.
3) Data consistency was checked, revealing inconsistencies in the Gender column. Men were represented as both 'M' and 'Men', while Women were represented as both 'Women' and 'W'.

## *Solutions:*
To rectify the inconsistencies:
i) All instances of 'Men' and 'Men' were replaced with 'M'.
ii) Similar steps were taken for other columns by identifying and correcting any inconsistent data.

## **Data Processing:**
The following data processing steps were implemented:
1) An age group categorization was created using a formula to represent different age categories.
   =IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))
2) The month was extracted from the date column using the formula:
   =TEXT(G2,"mmmm")

## **Data Analysis:**
The data analysis phase involved:
1) Creating pivot tables to answer specific questions.
2) Merging all pivot tables into one dashboard and incorporating slicers to make the dashboard interactive and dynamic.

## **Dashboard:**
 
## **Project Insight:**
The following insights were derived from the dashboards:
1) Women customers have a higher likelihood of purchasing products compared to men, accounting for approximately 65% of total sales.
2) The top three states with the highest product purchases are Maharashtra, Karnataka, and Uttar Pradesh.
3) The adult age group (30-49 years) makes the most significant contribution, representing approximately 50% of total sales.
4) The majority of customers place their orders through Amazon, Flipkart, and Myntra channels.

## **Final Conclusion:**
To enhance sales at Vrinda Stores, targeted efforts should focus on women customers within the age group of 30-49 years residing in Maharashtra, Karnataka, and Uttar Pradesh. Promotions such as ads, offers, and coupons should be prominently featured on Amazon, Flipkart, and Myntra platforms to effectively reach and engage this target audience.
