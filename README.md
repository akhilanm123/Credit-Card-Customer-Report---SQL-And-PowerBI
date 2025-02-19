# Credit-Card-Customer-Transaction-Report---SQL & PowerBI
###  Power BI | PostgreSQL | Data Analysis
## Project Overview
This project analyzes **credit card transactions and customer spending behavior** using **PostgreSQL** for data processing and **Power BI** for visualization. It provides valuable insights into **revenue trends, customer demographics, spending patterns, and transaction behaviors** to optimize financial strategies.

## Tools & Technologies Used + Resources
- **Power BI** – Interactive dashboards & visualizations
    - **Dashboard Interaction**: <a href="https://github.com/akhilanm123/Credit-Card-Customer-Transaction-Report-SQL-And-PowerBI/blob/main/Credit_Card_Customer_Transaction_Report.pbix">Credit-Card-Customer-Transaction-Report-SQL-And-PowerBI</a>
- **PostgreSQL** – Data extraction & transformation
    - **SQL Queries Used**:  <a href="https://github.com/akhilanm123/Credit-Card-Customer-Transaction-Report-SQL-And-PowerBI/blob/main/SQL%20Queries">SQL Queries</a>
- **DAX & SQL** – Data modeling & calculated measures
- **Excel/CSV** – Data preprocessing & formatting
    -  <a href="https://github.com/akhilanm123/Credit-Card-Customer-Transaction-Report-SQL-And-PowerBI/blob/main/credit_card.csv">Credit Card</a>
    -  <a href="https://github.com/akhilanm123/Credit-Card-Customer-Transaction-Report-SQL-And-PowerBI/blob/main/customer.csv">Customer</a>
###  Data Update & Refresh Process
To ensure that my **Power BI dashboards remain dynamic and up-to-date**, I implemented a **data refresh workflow**:
- **Excel File Updates**:
    - <a href="https://github.com/akhilanm123/Credit-Card-Customer-Transaction-Report-SQL-And-PowerBI/blob/main/cc_add.csv">cc_add</a>
    -  <a href="https://github.com/akhilanm123/Credit-Card-Customer-Transaction-Report-SQL-And-PowerBI/blob/main/cust_add.csv">cust_add</a>
- **SQL Integration & Data Processing**:
    - Updated Excel data is loaded into PostgreSQL.
    - SQL queries are executed to clean, transform, and structure the data for reporting.
- **Power BI Refresh Mechanism**:
    - The Power BI report is refreshed to pull the latest data from the SQL database.
    - Dynamic visuals get updated automatically, reflecting real-time changes.
- **Outcome**: This process ensures seamless data updates, allowing stakeholders to always access the most recent insights without manual intervention.
