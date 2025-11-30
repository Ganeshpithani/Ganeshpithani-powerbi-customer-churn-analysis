# Ganeshpithani-powerbi-customer-churn-analysis
📊 Customer Churn Analysis – Power BI Project
A complete end‑to‑end Power BI Data Analytics project built using a customer churn dataset.
This project covers data cleaning, modeling, DAX measures, dashboard design, and insight generation.

📝 Project Overview
Customer churn refers to when customers stop doing business with a company.
The aim of this project is to analyze why customers churn, identify key drivers, and build interactive dashboards to support data‑driven decisions.

📂 Dataset Description
The dataset includes demographic, service subscription, billing, and churn information.
Column	Description
customerID	Unique ID for each customer
gender	Male / Female
SeniorCitizen	1 = Yes, 0 = No
Partner	Yes / No
Dependents	Yes / No
tenure	Tenure in months
PhoneService	Yes / No
MultipleLines	Yes / No
InternetService	DSL / Fiber optic / No
OnlineSecurity	Yes / No
OnlineBackup	Yes / No
DeviceProtection	Yes / No
TechSupport	Yes / No
StreamingTV	Yes / No
StreamingMovies	Yes / No
Contract	Month‑to‑month / One year / Two year
PaperlessBilling	Yes / No
PaymentMethod	Payment method type
MonthlyCharges	Monthly bill
TotalCharges	Total bill to date
Churn	Yes / No

🛠️ Project Pipeline
1️⃣ Data Loading
Imported dataset into Power BI Desktop
Used Power Query for initial transformations

2️⃣ Data Cleaning
Performed inside Power Query Editor:
Removed blanks / nulls in TotalCharges
Converted datatypes correctly
Added conditional columns like:
Tenure Group
SeniorCitizenLabel
ChurnFlag

3️⃣ Data Modeling
Single‑table (star‑like) structure
Added relationships if necessary
Created important DAX measures:
Total Customers
Churned Customers
Churn Rate
Avg Tenure
Avg Monthly Charges

4️⃣ Dashboard Development
Created 4 dashboards:

🔹 Dashboard 1: Customer Demographics
Includes:
Cards → Total Customers, Churn Rate, Avg Charges, Avg Tenure
Pie chart → Gender Distribution
Bar chart → Senior Citizens vs Churn
Donut chart → Tenure Groups
Scatter plot → Monthly Charges vs Tenure
Slicers → Gender, Contract Type

🔹 Dashboard 2: Service Subscription Analysis
Includes:
Stacked bar → Internet Service vs Churn
Matrix → Add‑on services
Funnel → Service usage count
Heatmap → Service combinations
Slicers → Gender, Senior Citizen, Service Type

🔹 Dashboard 3: Contract & Billing Insights
Includes:
Clustered bar → Contract Type vs Churn
Donut → Payment Method
Column chart → Avg Total Charges by Contract
KPI Cards → Avg Monthly Charges, Total Charges
Histogram → Tenure by Contract Type

🔹 Dashboard 4: Churn Prediction & Key Drivers
Includes:
KPI → Overall Churn Rate
Bar chart → Top factors influencing churn
Customer segmentation visual
Revenue lost due to churn
AI-powered key influencers visual


🎯 Key Insights
Month‑to‑month customers churn significantly more
Fiber optic users show the highest churn rate
Customers with high monthly charges are more likely to churn
Long tenure customers rarely churn
Senior citizens have slightly higher churn compared to others
Auto‑payment customers churn less

🚀 Technologies Used
Power BI Desktop
Power Query
DAX
Data Modeling
GitHub

📬 How to Use This Project
Clone the repository
Open .pbix file in Power BI Desktop
Refresh the dataset
Explore dashboards and insights

⭐ If You Like This Project
Please give the repo a ⭐ star on GitHub!
