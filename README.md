# SupplyChain_EDA_Forecasting

## 🔹 Project Overview
This project performs a comprehensive **Supply Chain & Inventory Analysis** using Python. It demonstrates **Exploratory Data Analysis (EDA), ABC Inventory Classification, and Demand Forecasting** to provide actionable business insights for optimizing inventory and improving supply chain efficiency.


## 🔹 Features
- **Data Cleaning & Preprocessing:** Handle duplicates, missing values, and formatting issues.
- **Univariate & Bivariate Analysis:** Explore numeric and categorical features with clear grid-based visualizations.
- **Time Series Analysis:** Analyze monthly sales trends to detect seasonality.
- **ABC Inventory Analysis:** Classify products into A/B/C categories based on sales contribution.
- **Demand Forecasting:** Predict the next 6 months of product demand using **Holt-Winters Exponential Smoothing**.
- **Business Insights:** Actionable recommendations for inventory optimization and high-revenue product prioritization.


## 🔹 Dataset
- **Sample Dataset:** `supply_chain_sample.csv`
- Columns: `Order Date`, `Product Name`, `Category`, `Sales`, `Profit`, `Demand`, `Inventory`, `Supplier`.
- Rows: 120 (24 months × 5 products)
- Data is synthetic but realistic for demonstrating forecasting and ABC analysis.

## 🔹 Installation & Usage
1. Clone the repository:
```bash
git clone https://github.com/vanaja36/SupplyChain_EDA_Forecasting.git

## Install dependencies:
pip install pandas numpy matplotlib seaborn plotly statsmodels

## Key Insights

Top Products ('A' category): Drive majority of revenue → prioritize stock & marketing.

Moderate Products ('B' category): Maintain regular stock, monitor trends.

Low-Contribution Products ('C' category): Minimize inventory, reduce costs.

Demand Forecast: Predicts next 6 months, helping avoid overstock or stockouts.

Monthly Sales Trends: Identify seasonal peaks for strategic planning.

##🔹 Tools & Libraries

Python: Core programming

Pandas & NumPy: Data manipulation

Matplotlib & Seaborn: Visualization

Plotly: Interactive charts

Statsmodels: Time series forecasting (Holt-Winters)

##🔹 Repository Structure
SupplyChain_EDA_Forecasting/
│
├─ supply_chain_sample.csv       # Sample dataset
├─ SupplyChain_EDA_Forecasting.ipynb  # Jupyter notebook with full analysis
└─ README.md                     # Project description & instructions

##🔹 Skills Demonstrated

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Time Series Analysis & Forecasting

ABC Inventory Classification

Data Visualization & Insights Reporting

Business Intelligence & Decision Support
