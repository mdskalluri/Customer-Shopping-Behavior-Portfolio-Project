# Customer-Shopping-Behavior-Portfolio-Project
End-to-end data analytics project analyzing customer shopping behavior using Python for preprocessing, SQL for advanced insights, and Power BI for visualization. Identifies key trends in demographics, revenue, subscriptions, and product performance to drive data-driven business decisions.


## Introduction

In today’s retail environment, data-driven decision-making is essential for understanding customer behavior and improving business performance. This project analyzes customer shopping patterns to identify key trends in demographics, purchasing behavior, and revenue, enabling more effective marketing strategies and customer engagement.

## 📊 Dataset
The dataset consists of approximately 3,900 customer records, capturing both demographic and transactional details such as age, gender, product category, purchase amount, review ratings, and subscription status. This combination of features provides a comprehensive view of customer behavior, enabling meaningful analysis of purchasing patterns and trends.

## ⚙️ Tech Stack

- **Python** → Data preprocessing & EDA (Pandas, NumPy)  
- **SQL (MySQL)** → Advanced querying & insights  
- **SQLAlchemy & PyMySQL** → Database integration  
- **Power BI** → Interactive dashboard  

## 🔄 Workflow
**1. Data Preprocessing (Python)**

The raw dataset was first processed using Python to ensure data quality and consistency across all ~3,900 records. Missing values in the Review Rating column were handled using median imputation based on product categories, ensuring complete data without bias. Column names were standardized to improve readability and compatibility with SQL operations. Additionally, new features such as age groups were created to enable demographic segmentation, and redundant columns were removed to streamline the dataset for efficient analysis.

**2. Database Integration (MySQL)**

The cleaned dataset was then stored in a MySQL database using SQLAlchemy and PyMySQL. This step enabled structured storage and efficient querying of the data. By moving the dataset into a relational database, it became easier to perform complex aggregations, filtering, and business-level analysis using SQL.

**3. SQL Analysis**

Advanced analysis was performed using SQL to extract meaningful insights from the dataset. Queries were designed to evaluate revenue distribution across different segments such as gender and age groups, analyze subscription versus non-subscription behavior, and identify top-performing product categories. Customer segmentation analysis further helped in understanding retention patterns and identifying high-value customer groups.

**4. Visualization (Power BI)**

Finally, the insights were visualized using Power BI through an interactive dashboard. The dashboard includes charts such as donut charts, bar charts, and column charts to represent key metrics like revenue distribution, customer demographics, and subscription trends. Interactive filters and cross-analysis features allow users to dynamically explore the data, making it easier to interpret insights and support data-driven decision-making.

## 📊 Dashboard Insights

The Power BI dashboard provides a comprehensive overview of customer behavior, highlighting key metrics such as approximately 3,900 customers, an average purchase value of around $59, and an average review rating of 3.75, indicating stable customer engagement.

Revenue analysis shows that the Clothing category contributes over $100K (≈45–50% of total revenue), making it the dominant segment, followed by Accessories and Footwear. Demographic insights reveal that male customers account for nearly 68% of the customer base, contributing a significant share of revenue.

Subscription analysis highlights that only 27% of customers are subscribed, while 73% remain non-subscribers, indicating a major opportunity for growth. Additionally, age-based analysis shows that the Adult (26–46) group generates the highest revenue, reinforcing the importance of targeting this segment.

The dashboard uses donut charts, bar charts, and column charts, along with interactive filters, allowing users to dynamically explore trends across categories, demographics, and customer segments.

##💡 Business Insights

The analysis reveals that customer behavior is strongly influenced by demographics and product preferences, with the Adult (26–46) segment contributing the highest share of revenue and the Clothing category generating nearly 45–50% of total sales. While returning customers form a significant portion of the customer base, indicating strong retention, subscription adoption remains low at around 27%, highlighting a key opportunity for growth. Additionally, discount strategies are effective in increasing customer engagement and purchase value but should be optimized to maintain profitability. By focusing on targeted marketing for high-value segments and improving subscription offerings, the business can enhance customer lifetime value and overall performance.

##🚀 Conclusion

This project demonstrates a complete end-to-end data analytics workflow, integrating Python for data preprocessing, SQL for advanced analysis, and Power BI for visualization. By transforming raw data into meaningful insights, the project highlights how data-driven approaches can support better decision-making, improve customer engagement, and drive business growth in the retail domain.
