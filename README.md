# Telecom_Customer_Churn_Analysis:
## Project Description
This project is an end-to-end churn analysis built using Python, SQL, and Tableau to explore customer behavior and identify churn drivers in a telecom dataset (Kaggle: Telco Customer Churn).

Unlike a typical churn project, this analysis was intentionally designed to simulate a real business environment. I asked AI to generate realistic stakeholder questions, similar to what a retention manager or product owner would ask. These questions guided the entire workflow—from EDA to SQL segmentation to dashboard design.

The result is a stakeholder-driven churn insights dashboard, highlighting churn risk, service adoption patterns, payment friction, high-value customer loss, and tenure-based churn behavior.


## Dataset

Source: Kaggle - Teleco Customer Churn

Get the dataset from: [raw_data](Data.csv)

Key field used: ``customerID, gender, SeniorCitizen, Partner, Dependents, tenure, Contract, PaymentMethod, MonthlyCharges, TotalCharges, InternetService, Churn``

Notes:
- Handled missing values and type conversions .
- Created derived columns: `tenure_group`, `monthly_revenue_lost`


## Tools and libraries
- Dashboard: Tableau 
- Data cleaning & analysis: Python (pandas)
- Visuals & charts: Matplotlib,Seaborn and Tableau visuals
- Notebook: Jupyter Notebook 
- Version control & hosting: GitHub



## How to Run
1. **Clone the repo**   
```
git clone https://github.com/<your-username>/<repo-name>.git 
cd <repo-name> 
```
2. **Install dependencies**
This project uses common Python analytics libraries:
```
pip install pandas numpy matplotlib seaborn
```

3. **Run the Script**
   
``Run this inside your notebook``: [Telecom_Churn_Notebook.py](Telecom_Churn_Notebook.py)

4. **Dashboard**

   Open [dashboard](https://github.com/karthiksuresh-101/Project1-Telecom_Churn/blob/main/Project_details.md#dashboard)






## How to Explore the Analysis

#### This project is fully contained inside one notebook:

``Code.ipynb`` : [Notebook](Code.ipynb) 


This notebook includes the complete workflow:

- Data loading
- Preprocessing (missing values, data types, feature creation)
- Exploratory Data Analysis (EDA)
- VisualizationsChurn segment analysis
- Exporting cleaned data to connect with the dashboard




## Contact / About the author

Karthik Suresh — Data Analyst | Portfolio: (link to your Notion or portfolio)
Email: (your email) — LinkedIn: (your LinkedIn)






