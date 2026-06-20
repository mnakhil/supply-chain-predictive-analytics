📦 Supply Chain Analytics & Delivery Risk Prediction
📖 Project Overview
This project analyzes a large-scale Supply Chain dataset containing 180,519 orders to identify operational inefficiencies, evaluate delivery performance, understand profitability drivers, and predict delivery risks using Machine Learning.
The project combines:
•	Exploratory Data Analysis (EDA)
•	Data Cleaning & Feature Engineering
•	Business KPI Analysis
•	Delivery Performance Analysis
•	Profitability Assessment
•	Machine Learning Models
•	Interactive Power BI Dashboard
The objective is to provide actionable insights that help businesses improve logistics efficiency, reduce delivery delays, and increase profitability.
 
🎯 Business Problem
Supply chain organizations face several challenges:
•	High delivery delays
•	Increased logistics costs
•	Reduced customer satisfaction
•	Difficulty identifying risky shipments before dispatch
This project aims to answer:
1.	What factors contribute to delivery delays?
2.	How do delays impact profitability?
3.	Which orders are most likely to be delayed?
4.	How can business stakeholders monitor supply chain performance effectively?
 
📊 Dataset Information
Metric	Value
Total Records	180,519
Original Features	53
Final Features	23
Data Type	Supply Chain Operations
Target Variable	Delivery Risk / Delay Status
 
🧹 Data Cleaning & Preparation
The following preprocessing steps were performed:
Data Quality Checks
•	Removed duplicate information
•	Handled missing values
•	Removed low-information features
•	Eliminated redundant columns
Feature Selection
The dataset was reduced from 53 columns to 23 key features to improve model performance and interpretability.
Key Findings
•	Benefit per Order and Order Profit Per Order contained identical values.
•	Product Status contained only a single unique value and was removed.
•	Several columns with excessive missing values were excluded.
 
📈 Key Business KPIs
KPI	Value
Total Orders	180,519
Delayed Deliveries	98,743
Delay Rate	54.7%
Total Profit	$7.9 Million
Delay-Related Loss	$2.1 Million
Profitable Orders	145,558
Loss-Making Orders	33,784
 
🔍 Exploratory Data Analysis
Delivery Performance Analysis
Key Findings
•	More than half of all deliveries were delayed.
•	The most common delay was 1 day.
•	Severe delays (3+ days) significantly reduced profitability.
Insights
•	Logistics bottlenecks are concentrated in short-term delays.
•	Most delivery issues appear operational rather than structural.
 
Profitability Analysis
Findings
•	Approximately 80% of orders were profitable.
•	Delay-related inefficiencies contributed to substantial losses.
•	Profit margins decrease as delivery delays increase.
Business Impact
Reducing delays can directly improve:
•	Customer satisfaction
•	Operational efficiency
•	Profit margins
 
🤖 Machine Learning Models
The project includes delivery-risk prediction using supervised machine learning.
Random Forest
Metric	Score
Accuracy	74%
Precision	77%
Recall	74%
Advantages
•	Balanced performance
•	Strong recall
•	Effective for operational risk detection
 
XGBoost
Metric	Score
Accuracy	72%
Precision	85%
Recall	60%
Advantages
•	Higher precision
•	Lower false positive rate
Limitation
•	Misses more delayed shipments due to lower recall
 
🏆 Best Model
Random Forest
Random Forest was selected as the preferred model because supply chain risk prediction prioritizes identifying as many high-risk orders as possible.
Selected Model Accuracy: 74%
 
📊 Power BI Dashboard
The project includes a fully interactive Power BI dashboard consisting of:
Page 1 – Executive Overview
KPI Cards
•	Total Orders
•	Total Profit
•	Delay Rate
•	Delay Loss
•	Profitable Orders
•	Loss Orders
Visuals
•	Delivery Status Breakdown
•	Profitability Distribution
•	Business Performance Summary
 
Page 2 – Delivery Performance
Visuals
•	Delay Distribution
•	Shipping Mode Analysis
•	Regional Delay Analysis
•	Monthly Delay Trends
Filters
•	Region
•	Product Category
•	Shipping Mode
•	Customer Segment
 
Page 3 – Profit & Risk Analysis
Visuals
•	Profit by Category
•	Delay vs Profit Analysis
•	Machine Learning Model Comparison
•	Risk Prediction Metrics
 
🛠️ Tech Stack
Programming
•	Python
Libraries
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Scikit-Learn
•	XGBoost
Business Intelligence
•	Power BI
Development Environment
•	Jupyter Notebook
 
📂 Project Structure
Supply-Chain-Analytics/
│
├── data/
│   ├── supply_chain_data.csv
│
├── notebooks/
│   ├── EDA.ipynb
│
├── powerbi/
│   ├── Supply_Chain_Dashboard.pbix
│
├── reports/
│   ├── Supply_Chain_Report.pdf
│
├── images/
│   ├── profitability_analysis.png
│   ├── delay_distribution.png
│
├── README.md
│
└── requirements.txt
🚀 Future Improvements
•	Hyperparameter tuning
•	Real-time delivery risk monitoring
•	Deployment using Streamlit
•	Automated reporting pipeline
•	Supply chain forecasting models
•	Explainable AI (SHAP Analysis)
📌 Business Recommendations
1.	Reduce 1-day delivery delays through route optimization.
2.	Implement predictive risk scoring before shipment.
3.	Monitor delay-related losses as a strategic KPI.
4.	Develop regional logistics performance dashboards.
5.	Prioritize high-risk orders using machine learning predictions.
👨‍💻 Author
Anz
Data Analytics | Business Intelligence | Machine Learning
This project demonstrates the application of data analytics, predictive modeling, and dashboard development to solve real-world supply chain challenges.
📦 Supply Chain Analytics & Delivery Risk Prediction
📖 Project Overview
This project analyzes a large-scale Supply Chain dataset containing 180,519 orders to identify operational inefficiencies, evaluate delivery performance, understand profitability drivers, and predict delivery risks using Machine Learning.
The project combines:
•	Exploratory Data Analysis (EDA)
•	Data Cleaning & Feature Engineering
•	Business KPI Analysis
•	Delivery Performance Analysis
•	Profitability Assessment
•	Machine Learning Models
•	Interactive Power BI Dashboard
The objective is to provide actionable insights that help businesses improve logistics efficiency, reduce delivery delays, and increase profitability.
 
🎯 Business Problem
Supply chain organizations face several challenges:
•	High delivery delays
•	Increased logistics costs
•	Reduced customer satisfaction
•	Difficulty identifying risky shipments before dispatch
This project aims to answer:
1.	What factors contribute to delivery delays?
2.	How do delays impact profitability?
3.	Which orders are most likely to be delayed?
4.	How can business stakeholders monitor supply chain performance effectively?
 
📊 Dataset Information
Metric	Value
Total Records	180,519
Original Features	53
Final Features	23
Data Type	Supply Chain Operations
Target Variable	Delivery Risk / Delay Status
 
🧹 Data Cleaning & Preparation
The following preprocessing steps were performed:
Data Quality Checks
•	Removed duplicate information
•	Handled missing values
•	Removed low-information features
•	Eliminated redundant columns
Feature Selection
The dataset was reduced from 53 columns to 23 key features to improve model performance and interpretability.
Key Findings
•	Benefit per Order and Order Profit Per Order contained identical values.
•	Product Status contained only a single unique value and was removed.
•	Several columns with excessive missing values were excluded.
 
📈 Key Business KPIs
KPI	Value
Total Orders	180,519
Delayed Deliveries	98,743
Delay Rate	54.7%
Total Profit	$7.9 Million
Delay-Related Loss	$2.1 Million
Profitable Orders	145,558
Loss-Making Orders	33,784
 
🔍 Exploratory Data Analysis
Delivery Performance Analysis
Key Findings
•	More than half of all deliveries were delayed.
•	The most common delay was 1 day.
•	Severe delays (3+ days) significantly reduced profitability.
Insights
•	Logistics bottlenecks are concentrated in short-term delays.
•	Most delivery issues appear operational rather than structural.
 
Profitability Analysis
Findings
•	Approximately 80% of orders were profitable.
•	Delay-related inefficiencies contributed to substantial losses.
•	Profit margins decrease as delivery delays increase.
Business Impact
Reducing delays can directly improve:
•	Customer satisfaction
•	Operational efficiency
•	Profit margins
 
🤖 Machine Learning Models
The project includes delivery-risk prediction using supervised machine learning.
Random Forest
Metric	Score
Accuracy	74%
Precision	77%
Recall	74%
Advantages
•	Balanced performance
•	Strong recall
•	Effective for operational risk detection
 
XGBoost
Metric	Score
Accuracy	72%
Precision	85%
Recall	60%
Advantages
•	Higher precision
•	Lower false positive rate
Limitation
•	Misses more delayed shipments due to lower recall
 
🏆 Best Model
Random Forest
Random Forest was selected as the preferred model because supply chain risk prediction prioritizes identifying as many high-risk orders as possible.
Selected Model Accuracy: 74%
 
📊 Power BI Dashboard
The project includes a fully interactive Power BI dashboard consisting of:
Page 1 – Executive Overview
KPI Cards
•	Total Orders
•	Total Profit
•	Delay Rate
•	Delay Loss
•	Profitable Orders
•	Loss Orders
Visuals
•	Delivery Status Breakdown
•	Profitability Distribution
•	Business Performance Summary
 
Page 2 – Delivery Performance
Visuals
•	Delay Distribution
•	Shipping Mode Analysis
•	Regional Delay Analysis
•	Monthly Delay Trends
Filters
•	Region
•	Product Category
•	Shipping Mode
•	Customer Segment
 
Page 3 – Profit & Risk Analysis
Visuals
•	Profit by Category
•	Delay vs Profit Analysis
•	Machine Learning Model Comparison
•	Risk Prediction Metrics
 
🛠️ Tech Stack
Programming
•	Python
Libraries
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Scikit-Learn
•	XGBoost
Business Intelligence
•	Power BI
Development Environment
•	Jupyter Notebook
 
📂 Project Structure
Supply-Chain-Analytics/
│
├── data/
│   ├── supply_chain_data.csv
│
├── notebooks/
│   ├── EDA.ipynb
│
├── powerbi/
│   ├── Supply_Chain_Dashboard.pbix
│
├── reports/
│   ├── Supply_Chain_Report.pdf
│
├── images/
│   ├── profitability_analysis.png
│   ├── delay_distribution.png
│
├── README.md
│
└── requirements.txt
🚀 Future Improvements
•	Hyperparameter tuning
•	Real-time delivery risk monitoring
•	Deployment using Streamlit
•	Automated reporting pipeline
•	Supply chain forecasting models
•	Explainable AI (SHAP Analysis)
📌 Business Recommendations
1.	Reduce 1-day delivery delays through route optimization.
2.	Implement predictive risk scoring before shipment.
3.	Monitor delay-related losses as a strategic KPI.
4.	Develop regional logistics performance dashboards.
5.	Prioritize high-risk orders using machine learning predictions.
👨‍💻 Author
Anz
Data Analytics | Business Intelligence | Machine Learning
This project demonstrates the application of data analytics, predictive modeling, and dashboard development to solve real-world supply chain challenges.
