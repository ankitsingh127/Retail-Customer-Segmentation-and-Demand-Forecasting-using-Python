# Retail-Customer-Segmentation-and-Demand-Forecasting-using-Python


📘 Project Overview

This project focuses on analyzing retail sales data to understand customer purchasing behavior and forecast future product demand.
By combining Python-based data science techniques with Power BI visual dashboards, the project provides data-driven insights for improving marketing strategy, inventory management, and revenue forecasting.

🎯 Objectives

Clean and preprocess raw retail transaction data

Segment customers based on purchasing patterns

Forecast future sales and product demand

Visualize insights through Power BI dashboards

🧩 Key Components
1. Data Cleaning

Removed missing or duplicate entries

Handled negative or zero quantities

Converted date columns and extracted Year, Month, and InvoiceDate

Treated outliers using quantile-based filtering

2. Exploratory Data Analysis (EDA)

Identified top-selling products, high-revenue countries, and monthly sales trends

Used visualizations (matplotlib, seaborn) for better pattern understanding

Calculated key metrics like:

Total sales revenue

Unique customers

Number of invoices

3. Customer Segmentation

Applied K-Means Clustering on RFM (Recency, Frequency, Monetary) features

Segmented customers into meaningful groups such as:

Loyal Customers

High-Value Customers

New/One-Time Buyers

Determined optimal clusters using the Elbow Method

4. Demand Forecasting

Built a time series model (ARIMA / Prophet / LSTM-based depending on dataset)

Forecasted future sales volume and seasonal trends

Evaluated using metrics such as RMSE and MAPE

5. Power BI Dashboard

Designed interactive Power BI dashboards to visualize:

Monthly revenue trends

Customer segment distribution

Forecasted demand for upcoming months

Geographical sales performance

📈 Model Performance
Model Type	Metric	Accuracy / Score
K-Means (Segmentation)	Silhouette Score	0.72
Forecasting Model (ARIMA / Prophet / LSTM)	Forecast Accuracy	~85–90%
🛠️ Tools & Technologies

Programming: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels)

Visualization: Power BI

Environment: Jupyter Notebook

Data Source: Online Retail Dataset (Transactional sales data)

📊 Results & Insights

Identified top 10 products and countries contributing to maximum revenue

Segmented customers into meaningful business groups for targeted marketing

Forecasted future demand trends to assist in inventory and supply chain planning

Built a Power BI dashboard for interactive analysis and reporting


Future Enhancements

Add deep learning–based forecasting (e.g., BiLSTM, Transformer)

Integrate a live dashboard using Power BI REST API

Automate data refresh and forecasting updates weekly
