# Customer Shopping Behavior Analysis

![](https://github.com/KoreJosh/Customer-Bahavior-Analysis/assets/97749198/66ed50a2-ca69-4dfe-b4c7-0791ada82d44)

## Project Overview
The customer behavior analysis project aims to gain valuable insights into customer preferences, purchasing habits, and demographic trends by analyzing transactional data from various shopping malls. The dataset comprises the following columns: 'invoice_no', 'customer_id', 'gender', 'age', 'Age Group', 'category', 'quantity', 'price', 'payment_method', 'invoice_date', and 'shopping_mall'.

Key Objectives:

**Segmentation and Profiling**: Segment customers based on demographic factors such as gender, age, and shopping preferences. Profile each segment to understand their unique characteristics and preferences.

**Purchase Patterns Analysis**: Analyze purchase patterns, including frequency, recency, and monetary value of transactions. Identify popular product categories, preferred payment methods, and seasonal trends.

**Business Insights and Recommendations**: Generate actionable insights and recommendations based on analysis findings. Provide strategic recommendations to optimize marketing campaigns, improve customer engagement, and enhance overall business performance.

Leveraging advanced analytics techniques on the provided dataset, this project aims to empower businesses with actionable insights into customer behavior, enabling them to make data-driven decisions and drive sustainable growth in a competitive retail landscape.

## Data Source
The dataset contains 99457 rows( each rows represent a patient), and 15 columns of various shopping preferances.[See Here](https://github.com/KoreJosh/Customer-Bahavior-Analysis/files/14458583/customer_shopping_data.csv)


## Tools
- Python's Jupter notebook, Pandas, Tableau

## Data Cleaning / Preparation

- Data Loading and Inspection
  - Using the .shape(), it shows that the dataset has 99457 rows and 15 columns

- Handling missing values and duplicates
  - Using .isnull().sum() function, no missing values was recorded, also using the .duplicated().sum() function, no duplicate values was recorded.
 - Data transformation for the age column, grouping the customers age into Teenagers, Young Adults, Adults, Elders and Senior.
  - Data transformtion was also carried out on the date column, to get the month of purchase and day of purchase
      
## Exploratory Data Analysis

 **Demographic Analysis**:
   - Distribution of customers by gender and age groups.
   - Average age of customers and its variation across gender.
   - Male vs. female shopping preferences in terms of categories and shopping malls.

 **Category Analysis**:
   - Most popular product categories based on quantity sold and revenue generated.
   - Seasonal variations in category sales.
   - Cross-category purchasing behavior (e.g., which categories are often bought together).

 **Price Sensitivity**:
   - Distribution of price points and their impact on quantity sold.
   - Price elasticity analysis to understand how changes in price affect demand.

 **Payment Method Preferences**:
   - Distribution of payment methods used by customers.

 **Shopping Trends**:
   - Weekly, monthly, and yearly trends in shopping activities.
   - Peak shopping days.
   - Repeat purchase rate and customer loyalty trends.

 **Seasonal Analysis**:
   - Seasonal patterns in shopping behavior (e.g., holiday shopping trends).
   - Impact of seasonal events or promotions on sales.

By analyzing these aspects of the dataset, retailers can gain valuable insights into customer preferences, behaviors, and trends, enabling them to optimize marketing strategies, improve customer satisfaction, and drive business growth.


## Result / Findings
In our analysis of customer shopping behavior, we observed a consistent trend across all shopping malls, indicating a preference for clothing and associated accessories. These items emerged as the top-selling products, suggesting a high demand among customers. Notably, malls with a greater variety of clothing options experienced higher foot traffic and sales volumes.

Furthermore, our analysis revealed a distinct demographic pattern among shoppers. Individuals aged 40 and above emerged as the primary customer segment frequenting these malls. Interestingly, this trend was consistent across genders, with both male and female shoppers equally represented within this age group.

Overall, these findings highlight the significance of offering diverse clothing selections to cater to the preferences of our customer base, particularly among middle-aged and older demographics. Understanding these consumer preferences can inform strategic decisions aimed at maximizing sales and enhancing the overall shopping experience.

