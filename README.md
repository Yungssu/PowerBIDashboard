# PowerBIDashboard

# Falcon Dashboard

AtliQ Hardware, a growing hardware company, encountered issues with manual sales reporting and fragmented Excel files, resulting in inefficiencies and delayed decision-making. To address these difficulties, I created a Power BI dashboard that gives real-time sales data, automates reporting, and improves decision-making for stakeholders.

---

## 🔍 Analysis Overview  

1. **Data Overview**:
![Data Overview](https://github.com/Yungssu/PowerBIDashboard/blob/main/atliqERD.png)
            -The Entity Relationship Diagram (ERD) depicts AtliQ Hardware's Sales Insights Data Model. This model integrates multiple data tables to facilitate a comprehensive and efficient analysis of sales performance across products, markets, customers, and time periods. The central table, sales transactions, acts as a fact table, while the surrounding tables provide dimensional context.

- **sales transactions (Fact Table)**:
Contains detailed transactional data such as sales_amount, sales_qty, profit_margin, and order_date.
Serves as the central table connecting all dimensions for analysis.

- **sales products (Dimension Table)**:
Contains product details: product_code and product_type.
Linked to sales transactions via product_code.

- **sales customers (Dimension Table)**:
Provides customer details: customer_name, customer_code, and customer_type.
Linked to sales transactions through customer_code.

- **sales markets (Dimension Table)**:
Contains geographical details: markets_code, markets_name, and zone.
Linked to sales transactions via market_code.

- **sales date (Time Dimension Table)**:
Holds date-related information: date, month_name, year, and date_yy_mmm.
Linked to sales transactions via order_date.

- **base_measures (Supporting Table)**:
Includes a pre-calculated measure: Revenue, for advanced reporting.

3. **Key Insights**:
   - Determined the most popular content category by analyzing aggregate user reaction scores.  
   - Ranked the Top 5 content categories based on user engagement metrics.  
   - Identified the month with the highest number of posts, highlighting seasonal posting trends.  

## 📊 Results  

### Total Scores per Category
![Results](https://github.com/Yungssu/PowerBIDashboard/blob/main/AtliqDashboard.png)
   - The "Animals" category won overall, and gained the most points. The remaining top-performing categories, in order, were "Science," "Healthy Eating," "Technology," and "Food." These are some of the top categories in terms of user engagement and interest, and they present categories of focus for Social Buzz in terms of activity on the platform and growth.

### Top 5 "popular" Category  
![Results](https://github.com/Yungssu/ExcelAnalysis/blob/main/SocialBuzzTop5.png)
   - Among the five leading performance categories, two related directly to food were “Healthy Eating” and “Food.” This also shows a significant user interest in food and nutrition content.
### Total Posts per Month  
![Results](https://github.com/Yungssu/ExcelAnalysis/blob/main/SocialBuzzPostsPerMonth.png)
   - This graph illustrates the monthly posting trends on Social Buzz, showing fluctuations in the number of posts throughout the year. The data reveals peak activity in January, May, and July, with dips in February and October. These trends highlight opportunities for aligning content campaigns with months of increased posting activity.

## 💡 Recommendations

Based on the insights gathered from analyzing Social Buzz's data:

1. **Focus on Top-Performing Categories**  
   - Makes the site categories as listed, the Animals, Science, Healthy Eating, Technology and Food areas, have the highest total popularity for the topics within them.
   - Tailor campaigns and partnerships that align with these niches to maintain and increase user engagement, allowing Social Buzz to hone its advantage in these high-performance areas.

2. **Leverage Food-Related Content**  
   - Social Buzz can partner with food influencers to take engagement to the next level as "Healthy Eating" and "Food" joined the top five categories.
   - Adding subcategories to these niches is creating more potentially desirable content that would appeal to a wide format while retaining its core market, and driving more engagement across food content on the platform.

4. **Seasonal Posting Strategies**  
   - Analyze monthly posting trends to identify peak periods and synchronize major content campaigns with these high-traffic months, maximizing visibility.  
   - Focus on promoting specific categories, such as "Animals" and "Science," during their peak engagement months to optimize user interaction and capitalize on content popularity.

5. **Enhance Data-Driven Decision Making**  
   - Leverage data insights to enhance content recommendation algorithms, ensuring users are served content that aligns with their interests and engagement patterns.  
   - Invest in advanced content curation tools that utilize these insights to prioritize and highlight trending topics, improving user experience and driving sustained engagement on the platform.


## 🛠️ Tools Used  

- **Excel**: Data Cleaning and Pivot Tables  
- **Markdown**: For project documentation  

---

## 🔗 Portfolio Link  
[Back to My Portfolio][(https://github.com/Yungssu/kennethHuyong.github.io)

