# PowerBIDashboard

# Falcon Dashboard

AtliQ Hardware, a growing hardware company, encountered issues with manual sales reporting and fragmented Excel files, resulting in inefficiencies and delayed decision-making. To address these difficulties, I created a Power BI dashboard that gives real-time sales data, automates reporting, and improves decision-making for stakeholders.

---

## 🔍 Analysis Overview  

 **Data Overview**:
![Data Overview](https://github.com/Yungssu/PowerBIDashboard/blob/main/atliqERD.png)
   - The Entity Relationship Diagram (ERD) depicts AtliQ Hardware's Sales Insights Data Model. This model integrates multiple data tables to facilitate a comprehensive and efficient analysis of sales performance across products, markets, customers, and time periods. The central table, sales transactions, acts as a fact table, while the surrounding tables provide dimensional context.

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

##  Process  

1. **AIMS Grid Project Planning**

- **Purpose**: Automate sales reporting and provide actionable insights.
- **Stakeholders**: Sales Team, IT Team (Falcons), and Data Analytics Team (Data Masters).
- **End Result**: An interactive Power BI dashboard for real-time sales tracking.
- **Success Criteria**:
   - Reduce manual work and costs by 10%.
   - Increase sales by 5% within 3 months.
     
2. **Data Integration**

- **Connected Power BI directly to the MySQL database storing sales records**.
- **Simplified ETL**: Performed transformations such as filtering, cleaning, and removing unnecessary columns within Power BI.
  
3. **Dashboard Development**

- **Designed intuitive visualizations to display**:
   - Sales trends and performance metrics.
   - Regional and product-level breakdowns.
   - Real-time data for decision-makers.


## 📊 Dashboard

### Total Scores per Category
![Results](https://github.com/Yungssu/PowerBIDashboard/blob/main/AtliqDashboard.png)

- **Reduced dependency on manual Excel processes, saving time and resources**.
- **Provided real-time insights to help regional managers and the sales director make data-driven decisions**.
- **Improved operational efficiency and aligned sales tracking with organizational goals**.

## 💡 Outcome

- **The project streamlined AtliQ Hardware’s sales reporting process and empowered the team with automated, actionable insights, achieving the desired success metrics**.



## 🛠️ Tools Used  

- **SQL**: Data Cleaning  
- **Power BI**: Data Visualization 

---

## 🔗 Portfolio Link  
[Back to My Portfolio][(https://github.com/Yungssu/kennethHuyong.github.io)

