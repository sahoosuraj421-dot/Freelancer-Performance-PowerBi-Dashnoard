# Freelance Operations & Performance Dashboard  
**Power BI Analytics with Machine Learning Cost & Delay Prediction**

## Project Overview
This project presents an end-to-end **data analytics and machine learning solution** for analyzing freelance platform operations. It integrates historical job data, financial metrics, client and freelancer analytics, and machine learning–based predictions into an interactive **Power BI dashboard**.

The dashboard is designed to support **business decision-making**, operational monitoring, and future forecasting for freelance platforms.

---

## Objectives
- Analyze freelance job performance across platforms
- Track revenue, cost overruns, and delivery efficiency
- Monitor client and freelancer behavior
- Identify operational risks and inefficiencies
- Predict **future job cost** and **job delay/status** using ML models

---

## Dashboard Pages
1. **Executive Overview**
   - Total Jobs, Completed Jobs, In-Progress Jobs
   - Average Job Duration
   - On-Time Delivery %
   - Job trends by Year, Quarter, Month, Platform, Category

2. **Platform Performance**
   - Total Revenue
   - Average Platform Fee %
   - Revenue by Platform, Verification Level, Country, Gender
   - Monthly revenue trends

3. **Financial Insights**
   - Total Budget vs Actual Spend
   - Budget Utilization %
   - Cost Overrun Rate %
   - Spend analysis by Platform, Client Type, Job Category

4. **Client Analytics**
   - Total, Active, and Churned Clients
   - Client Retention %
   - Average Jobs per Client
   - Average Client Spend
   - Client distribution by Status, Type, Tier, Category

5. **Freelancer Analytics**
   - Total and Active Freelancers
   - Average Rating and Hourly Rate
   - Completion %
   - Freelancer distribution by Experience Level and Platform Tier

6. **Prediction (ML Insights – 2026)**
   - Predicted vs Actual Job Cost
   - Cost prediction by Job Category, Client Status, Client Size
   - Predicted Job Status (Completed / In Progress / Cancelled)
   - Revenue impact based on predicted outcomes

---

## Machine Learning
Supervised learning models were trained on historical data to generate predictions.

### ML Tasks
- Regression: Predict `Predicted_Cost_USD`
- Classification: Predict job delay / job status

### Algorithms Used
- Linear Regression
- Random Forest Regressor
- Random Forest Classifier

### Feature Engineering
- Time-based features (Year, Quarter, Month)
- Encoded categorical variables
- Cost overrun and delay indicators

---

## Tech Stack
- **Python**: pandas, numpy, scikit-learn
- **Machine Learning**: Random Forest, Linear Regression
- **Visualization**: Power BI Desktop
- **Database (optional)**: PostgreSQL
- **Analytics**: DAX Measures

---

## Dataset Overview
The dataset represents freelance job activity across multiple platforms.

**Key Columns**
- Job Details: Job_ID, Job_Status, Job_Category, Project_Type
- Time Metrics: Job_Duration_Days, Time_To_Hire_Days
- Financials: Budget_USD, Actual_Cost_USD, Platform_Revenue_USD
- Client Data: Client_Type, Client_Status, Client_Size_Label
- Freelancer Data: Experience_Level, Rating, Hourly_Rate
- Platform Data: Platform, Platform_Tier, Verification_Level

---

## Key KPIs
- Total Jobs
- Completed Jobs
- In-Progress Jobs
- Average Job Duration
- On-Time Delivery %
- Total Revenue
- Budget Utilization %
- Cost Overrun Rate %
- Client Retention %

---

## How to Use
1. Open the `.pbix` file in **Power BI Desktop**
2. Use slicers to filter by Platform, Country, Client Type, and Project Type
3. Navigate between pages for detailed insights
4. Review the **Prediction** page for ML-generated forecasts

---

## Business Value
- Data-driven operational monitoring
- Early identification of high-risk jobs and clients
- Improved revenue and cost control
- Demonstrates real-world integration of **Machine Learning + Business Intelligence**

---

## Author
**Suraj Sahoo**  
MSC – Information Technology
Skills: Python, SQL, Power BI, Machine Learning

---

## Disclaimer
This project is created for **educational and portfolio purposes**.  
The dataset used is **synthetic / anonymized** and does not represent real client data.
