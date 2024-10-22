# LITA_Class_Documentation
### Project Title: PIZZA SALES PERFORMANCE ANALYSIS

[Project Overview](#project-overview).

[Data Sources](#data-sources).

[Tools Used](#tools-used).

[Data Cleaning and Preparations](#data-cleaning-and-preparations).

[Exploratory Data Analysis](#exploratory-data-analysis).

[Data Analysis](#data-analysis).

[Data Visualization](#data-visualization).

[Conclusion](#conclusion).

### Project Overview

This project analyzes pizza sales data to understand how customers order, which pizza sizes they prefer, when the busiest times are, and how pricing affects sales. The insights from this analysis will help improve marketing, manage inventory more efficiently, and boost customer satisfaction.

---
### Data Sources  

The data for this analysis comes from the *Pizza Sales.csv* file, which was freely downloaded from *Kaggle.com*.

---

### Tools Used

- Microsoft Excel [Download Here](https://www.mircosoft.com).

1. For Data Cleaning
2. For Data Analysis
3. For Data Visualization
   
- SQL: Structured Query Language for Querying of Data
  
- GitHub for Porfolio Building

---

### Data Cleaning and Preparations

For this dataset, I performed several key actions to ensure the data was ready for analysis:

- Removed duplicates to prevent overcounting.
- Handled missing values by either filling them in or removing incomplete records.
- Used the "Find and Replace" function to correct inconsistent data entries (e.g., formatting issues or typos).
- Standardized column names for consistency and readability.
- Converted data types (e.g., date and time formats) to ensure proper analysis.
- Filtered out any irrelevant data that did not contribute to the analysis.

---
### Exploratory Data Analysis

During the EDA, the data was explored to address the following key questions:

- Which pizza size is the most preferred by customers?
- Which pizza category (e.g., Classic, Chicken, Supreme) is the most popular?
- What day of the week sees the highest sales volume?
- What month records the most sales?
- Which specific pizza name is the most frequently ordered by customers?

---

### Data Analysis

During my analysis, I utilized the following SQL query to determine the number of orders for each pizza size: 

```SQL
SELECT pizza_size, COUNT(*) AS order_count
FROM pizza_sales
GROUP BY pizza_size
ORDER BY order_count DESC;
```

The analysis of the pizza sales data provided key insights into customer preferences and sales patterns, focusing on pizza size, category, time of purchase, and specific popular pizzas. Below are the findings:

1. Pizza Size Preferences: The Large pizza size was the most preferred by customers, followed by Medium and Small. This suggests that customers often order larger pizzas, likely for sharing or feeding more people.
2. Popular Pizza Categories: The Classic pizza category was the most popular among customers, followed by Chicken and Supreme pizzas. These insights help tailor the menu and promotions to customer preferences.
3. Day of the Week with Highest Sales: Fridays recorded the highest number of orders, making it the busiest day of the week. This suggests a preference for pizza as a weekend meal, especially at the start of the weekend.
4. Month with the Most Sales: January recorded the highest total sales, followed by March and November. This indicates strong demand in these months, possibly due to the post-holiday period and other seasonal factors.
5. Top-Selling Pizza Name: The Classic Deluxe Pizza was the most frequently ordered pizza, with a total quantity of 2,453 sold. This indicates strong customer preference for this specific variety, which can drive targeted promotions and highlight popular menu items to boost sales further.

---
### Data Visualization
[Pizza Size Preferences](https://github.com/user-attachments/assets/dfa047c8-74e1-471e-a5a3-14dd2237a0bb)

[Most Frequently Ordered Pizza](https://github.com/user-attachments/assets/315cf426-7b6b-40aa-adad-750197092a71)

[Popular Pizza Categories](https://github.com/user-attachments/assets/ce66278e-1905-4b2f-ab77-ba300c41bd22)

[Month with Most Sales](https://github.com/user-attachments/assets/c9f60e90-ab40-42ce-a68c-1ce1725f9092)

[Days of the Week with HIghest Sales](https://github.com/user-attachments/assets/25434d7c-d235-4413-8d50-955c55f4de8a)

---
### Conclusion

The pizza sales analysis revealed key insights: **Large** pizzas and the **Classic** category were the most popular, with sales peaking on **Fridays** and during **dinner hours**. **January** had the highest sales, and **The Classic Deluxe Pizza** was the top seller. These findings can guide targeted promotions, inventory management, and staffing to better align with customer demand, boosting sales and operational efficiency.

---







