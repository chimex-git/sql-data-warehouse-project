## SQL DATA WAREHOUSE AND ANALYTICS PROJECT
This project showcases the integration of Business Intelligence (BI) and Data Engineering (ETL) principles to transform raw financial data into actionable insights.

## CONTENTS
transaction table schema
merchants table schema
users table schema
accounts table schema
sample data inserts
example queries

## BUSINESS INTELLIGENCE(BI) ASPECT
The business intelligence layer focuses on uncovering insights that can guide strategic decisions. By linking transactions to user and merchant profiles, the analysis enables:

Revenue Analysis: Identify which merchants drive the highest transaction volume and value.

User Behavior Insights: Understand spending trends by user demographics, activity frequency, or account type.

Performance Monitoring: Visualize KPIs such as average transaction value, customer retention rate, and merchant growth.

The data can be visualized using tools such as Power BI, Tableau, or Looker, providing dashboards that display:

Top-performing merchants

Monthly transaction growth

User engagement metrics

Account-to-merchant relationships

By structuring the database with relational integrity between entities (Users → Accounts → Transactions → Merchants), the project forms the analytical backbone for scalable BI reporting.

## DATA ENGINEERING (ETL) ASPECT
The ETL(EXTRACT, TRANSFORM AND LOAD) pipeline explains the project’s analytics by ensuring data is clean, consistent, and ready for analysis.

Extract:
Raw CSV files (transactions.csv, merchants.csv, users.csv, accounts.csv) are extracted from various operational systems representing financial and user activities.

Transform:
Data cleaning and transformation occur to ensure standardization, correcting inconsistencies, handling missing values, and enforcing referential integrity.
Typical transformations include:

Joining tables on shared keys (e.g., user_id, account_id, merchant_id).

Calculating derived metrics like total transaction value per merchant or per account.

Normalizing date fields and monetary values for time-series analysis.

Load:
The transformed data is loaded into structured database tables (e.g., Employee, Bonus, Transaction, etc.) within a data warehouse environment. This enables fast querying and seamless integration with BI tools.

This ETL process ensures the entire data lifecycle; from ingestion to visualization remains automated, reliable, and scalable.
