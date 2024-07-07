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

## Dashboard Summary
![Customer Behavior Dashboard](https://github.com/KoreJosh/Customer-Bahavior-Analysis/blob/main/customer%20Analysis.png)

### Key Metrics
Total Customers: 99,457
Total Quantity: 298,712
Total Price: 68,551,366

### Analysis Components
1. Profitability at a Glance for All Malls
#### Purchase By Gender:

Male: 40.19%
Female: 59.81%

#### Purchasing Power Based on Age Group:

Adult: 13,234,917
Elder: 13,279,029
Senior: 24,833,266
Teenager: 1,211,464
Young Adult: 15,992,690

#### Customer By Product Category:

Books: 4,981
Clothing: 34,487
Cosmetics: 15,097
Food & Beverages: 14,776
Shoes: 10,034
Souvenirs: 4,999
Technology: 30,217
Toys: 10,087

#### Quantity of Product Category:

Books: 14,982
Clothing: 103,558
Cosmetics: 45,465
Food & Beverages: 44,277
Shoes: 15,021
Souvenirs: 10,034
Technology: 30,217
Toys: 30,321

#### Payment Method:
Cash: 30,705,031
Credit Card: 24,051,477
Debit Card: 13,794,858

2. Customer Purchase Patterns 
#### Customer Purchase By Month:
Shows the trend of customer purchases from January 2021 to March 2023.

3. Product Pricing
#### Product Category Based on Average Pricing:
Books: 901
Clothing: 1,807
Cosmetics: 1,122
Food & Beverages: 1,612
Shoes: 35
Souvenirs: 108
Technology: 3,157
Toys: 46

### Product Quantity by Mall:
While malls such as (Kanyon,Mall of Istanbul,Metropol AVM,Istinye Park,Metrocity) had more product quantity thand the rest they also experienced more pathtonage as seen in the customer by mall analysis.

4. Demographics
### Age Group of Customers:
Young Adult: 23.3%
Adult: 19.4%
Elder: 19.2%
Senior: 36.3%

Interact with the Analysis [Here](https://public.tableau.com/app/profile/korede.joshua/viz/CustomerBehaviorAnalysis_17087952173620/Dashboard1?publish=yes)

### Insights and Recommendations
Purchasing Trends: Senior customers have the highest purchasing power, indicating that marketing strategies should target this age group.
Gender Distribution: Female customers make up a larger percentage of the customer base, suggesting that product offerings and promotions should cater to their preferences.
Product Preferences: Clothing and technology are the most popular product categories, so expanding inventory in these areas could be beneficial.
Payment Methods: Cash is the most preferred payment method, followed by credit cards. Ensuring smooth transactions for these methods can enhance customer experience.
Mall-Specific Strategies: Each mall has unique customer demographics and product preferences, requiring tailored marketing and inventory strategies.

## Result / Findings
In our analysis of customer shopping behavior, we observed a consistent trend across all shopping malls, indicating a preference for clothing and associated accessories. These items emerged as the top-selling products, suggesting a high demand among customers. Notably, malls with a greater variety of clothing options experienced higher foot traffic and sales volumes.

Furthermore, our analysis revealed a distinct demographic pattern among shoppers. Individuals aged 40 and above emerged as the primary customer segment frequenting these malls. Interestingly, this trend was consistent across genders, with both male and female shoppers equally represented within this age group.

Overall, these findings highlight the significance of offering diverse clothing selections to cater to the preferences of our customer base, particularly among middle-aged and older demographics. Understanding these consumer preferences can inform strategic decisions aimed at maximizing sales and enhancing the overall shopping experience.

