# 📦 Supply Chain Analytics & Delivery Risk Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-RandomForest-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📊 Project Overview

This project analyzes **180,519 supply chain orders** to identify operational inefficiencies, evaluate delivery performance, understand profitability drivers, and predict delivery risks using Machine Learning.

The project combines:

- 📈 Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning & Feature Engineering
- 📊 Business KPI Analysis
- 🚚 Delivery Performance Analysis
- 💰 Profitability Assessment
- 🤖 Machine Learning Models
- 📉 Interactive Power BI Dashboard

---

# 🎯 Business Objective

Supply chain organizations often face:

- High delivery delays
- Increased logistics costs
- Reduced customer satisfaction
- Difficulty identifying high-risk orders

This project aims to:

✅ Understand delivery performance

✅ Measure profitability impact

✅ Predict delivery risks

✅ Build an executive dashboard for decision-making

---

# 📌 Key Performance Indicators

| KPI | Value |
|-------|--------|
| Total Orders | 180,519 |
| Delayed Orders | 98,743 |
| Delay Rate | 54.7% |
| Total Profit | $7.9 Million |
| Delay Related Loss | $2.1 Million |
| Profitable Orders | 145,558 |
| Loss Making Orders | 33,784 |

---

# 📊 Dashboard Preview

## Executive Overview

![Dashboard Overview](images/dashboard_overview.png)

Features:

- KPI Cards
- Delay Analysis
- Profitability Insights
- Interactive Filters

---

## Delivery Performance Analysis

![Delivery Dashboard](images/delivery_dashboard.png)

Key Metrics:

- Delay Rate
- Shipping Mode Analysis
- Regional Performance
- Monthly Trends

---

## Profit & Risk Analysis

![Risk Dashboard](images/risk_dashboard.png)

Highlights:

- Profit by Category
- Delay Impact on Profit
- Machine Learning Performance
- Delivery Risk Prediction

---

# 📈 Exploratory Data Analysis

## Delivery Status

```text
Delayed Deliveries  : 54.7%
On-Time Deliveries  : 45.3%
```

### Key Insight

More than half of all orders experienced delivery delays.

---

## Profitability Analysis

```text
Profitable Orders   : 145,558
Loss Orders         : 33,784
```

### Key Insight

The business remains profitable overall but experiences substantial losses due to delayed deliveries.

---

# 🤖 Machine Learning Models

## Random Forest

| Metric | Score |
|----------|----------|
| Accuracy | 74% |
| Precision | 77% |
| Recall | 74% |

---

## XGBoost

| Metric | Score |
|----------|----------|
| Accuracy | 72% |
| Precision | 85% |
| Recall | 60% |

---

# 🏆 Best Performing Model

### Random Forest

Reason:

- Better Recall
- Balanced Performance
- More suitable for supply chain risk prediction

```text
Accuracy  : 74%
Precision : 77%
Recall    : 74%
```

---

# 🛠️ Technologies Used

## Programming

- Python

## Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
```

## Visualization

- Power BI
- Matplotlib
- Seaborn

## Environment

- Jupyter Notebook

---

# 📂 Project Structure

```text
Supply-Chain-Analytics
│
├── data
│   └── supply_chain_data.csv
│
├── notebooks
│   └── Supply_Chain_EDA.ipynb
│
├── powerbi
│   └── Supply_Chain_Dashboard.pbix
│
├── images
│   ├── dashboard_overview.png
│   ├── delivery_dashboard.png
│   ├── risk_dashboard.png
│   ├── profitability_chart.png
│   └── delay_distribution.png
│
├── reports
│   └── Supply_Chain_Report.pdf
│
├── requirements.txt
│
└── README.md
```

---

# 🚀 Power BI Features

### Executive Dashboard

- Total Orders
- Profit
- Delay Rate
- Loss Analysis

### Interactive Filters

- Region
- Product Category
- Customer Segment
- Shipping Mode

### Advanced Analytics

- Drill Through Pages
- Dynamic KPIs
- Tooltips
- Cross Filtering

---

# 📌 Business Recommendations

### 1. Reduce 1-Day Delays

Most delays occur within one day.

Actions:

- Improve warehouse dispatch
- Optimize route planning

---

### 2. Deploy Predictive Models

Use Random Forest to identify high-risk deliveries before shipment.

---

### 3. Monitor Delay Costs

Create a KPI:

```text
Cost of Delay per Order
```

to track operational efficiency.

---

### 4. Regional Performance Monitoring

Track:

- Delay Rate by Region
- Profit by Region
- Shipping Performance

---

# 📈 Future Improvements

- Real-Time Dashboard
- Streamlit Deployment
- Forecasting Models
- Explainable AI (SHAP)
- Automated Reporting

---

# 👨‍💻 Author

### Anz

Data Analytics | Business Intelligence | Machine Learning

This project demonstrates the use of Data Analytics, Machine Learning, and Business Intelligence techniques to solve real-world supply chain challenges.

---

⭐ If you found this project useful, consider giving it a star.