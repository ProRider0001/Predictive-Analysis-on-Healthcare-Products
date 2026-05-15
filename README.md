# Predictive Analysis on Healthcare Products

## 📌 Overview

Predictive Analysis on Healthcare Products is a Business Intelligence and Forecasting project developed using **Microsoft Power BI**, **Python**, and **R** to analyze healthcare product sales and predict future demand using the **ARIMA forecasting model**.

The project helps organizations understand sales trends, optimize inventory management, improve supply chain planning, and support data-driven business decisions through interactive dashboards and predictive analytics.

---

# 🎯 Objectives

* Analyze healthcare product sales trends using historical data
* Forecast future product demand using ARIMA time-series forecasting
* Visualize sales performance across products, customers, and regions
* Support inventory and supply chain optimization
* Provide business insights through interactive dashboards

---

# 🚀 Features

* 📊 Interactive Power BI Dashboards
* 📈 ARIMA-based Sales Forecasting
* 🗺️ Geographical Sales Analysis using Map Visuals
* 📉 Sales Trend Visualization using Python
* 🔍 Autocorrelation Analysis using R
* 🧩 Star Schema Data Modeling
* 🔄 ETL (Extract, Transform, Load) Data Processing
* 📦 Inventory & Demand Planning Insights

---

# 🛠️ Technology Stack

| Category                | Technology         |
| ----------------------- | ------------------ |
| Business Intelligence   | Microsoft Power BI |
| Programming Languages   | Python, R          |
| Visualization Libraries | Matplotlib         |
| Forecasting Model       | ARIMA              |
| Data Modeling           | Star Schema        |
| Data Analysis           | Power Query, DAX   |

---

# 📂 Dataset

The project uses healthcare product sales datasets including:

* Sales History
* Customer Master Data
* Product Master Data
* Location Master Data

---

# 📁 Project Structure

```bash
Predictive-Analysis-on-Healthcare-Products/
│
├── Data/
│   ├── Sales_History.csv
│   ├── Customer_Master_Data.csv
│   ├── Product_Master_Data.csv
│   └── Location_Master_Data.csv
│
├── PowerBI/
│   └── Healthcare_Sales_Dashboard.pbix
│
├── Python_Code/
│   └── sales_distribution.py
│
├── R_Code/
│   └── arima_forecasting.R
│
├── Images/
│   ├── dashboard.png
│   ├── forecast.png
│   └── map_visual.png
│
└── README.md
```

---

# 📊 Data Analysis & Visualizations

## 🔹 Geographical Demand Distribution

Analyzed sales distribution geographically using Power BI Map Visuals and ArcGIS maps.

## 🔹 Sales History Distribution

Visualized monthly and daily sales distribution using Python visuals integrated into Power BI.

## 🔹 Autocorrelation Analysis

Performed autocorrelation analysis using R libraries to validate time-series dependencies before forecasting.

## 🔹 Sales Forecasting

Implemented ARIMA forecasting model to predict healthcare product demand for the next 12 months.

---

# 🧠 ARIMA Forecasting Model

The ARIMA model uses:

* **p** → Lag observations
* **d** → Degree of differencing
* **q** → Moving average order

This model is effective for forecasting non-seasonal time-series sales data.

---

# 📈 Benefits of the Project

* Improves demand forecasting accuracy
* Reduces inventory and manufacturing costs
* Supports strategic business planning
* Enhances supply chain management
* Helps maintain optimal stock levels
* Enables data-driven decision-making

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone <repository-url>
cd Predictive-Analysis-on-Healthcare-Products
```

## 2️⃣ Install Python Dependencies

```bash
pip install pandas matplotlib numpy
```

## 3️⃣ Install R Libraries

```R
install.packages("forecast")
install.packages("tseries")
```

## 4️⃣ Open Power BI Dashboard

Open the `.pbix` file in Microsoft Power BI Desktop.

---

# 📌 Future Enhancements

* Real-time healthcare sales forecasting
* Machine Learning-based predictive models
* Interactive web dashboard deployment
* Cloud database integration
* Automated reporting system

---



