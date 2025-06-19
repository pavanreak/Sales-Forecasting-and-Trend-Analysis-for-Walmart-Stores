# 🛒 Walmart Sales Forecasting & Store Performance Analysis

This capstone project focuses on analyzing and forecasting weekly sales data for Walmart stores across the U.S. using historical sales data and external economic indicators.

---

## 📊 Project Objective

- Explore patterns in weekly sales data
- Evaluate the impact of holidays, unemployment rate, CPI, and temperature
- Identify top and bottom performing stores
- Forecast weekly sales for the next 12 weeks for each store

---

## 🛠️ Tools & Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Google Colab
- Linear Regression
- Time Series Analysis

---

## 📁 Dataset Features

| Column Name       | Description |
|-------------------|-------------|
| Store             | Store ID |
| Date              | Week ending date |
| Weekly_Sales      | Total sales for the week |
| Holiday_Flag      | Whether the week is a holiday week |
| Temperature       | Average temperature |
| Fuel_Price        | Regional fuel cost |
| CPI               | Consumer Price Index |
| Unemployment      | Unemployment rate |

---

## 📈 Key Analyses Performed

- **Correlation Analysis** between Weekly Sales and:
  - Unemployment Rate
  - CPI
  - Temperature
  - Holidays
- **Store Ranking** by total and average weekly sales
- **Seasonality Check** (e.g. holiday spikes, year-end trends)
- **Forecasting** of next 12 weeks of sales using Linear Regression

---

## 📌 Key Insights

- 📉 Slight negative correlation between Unemployment Rate and Weekly Sales
- 🎉 Holiday weeks showed a clear spike in sales
- 🥵 Temperature and CPI had store-wise varying effects
- 🏬 Store 20 was the highest performing; Store 33 was among the lowest
- 📅 Seasonal trends show peak sales around November–December

---

## 🔮 Forecasting

Used **Linear Regression** to train individual models for each store and predict their weekly sales for the next 12 weeks. Visualizations for each store were generated comparing historical and forecasted sales.

---

## 📊 Sample Forecast Visualization

> Store 1 — Historical vs Forecasted Sales  
![Store 1 Forecast]
![Screenshot 2025-06-19 150716](https://github.com/user-attachments/assets/6e8148f8-bcc6-4231-888f-009805676f56)


---

## 📂 Folder Structure
"D:\Downloads\Walmart_Project.ipynb"
"D:\Datasets & Projects\projects\Walmart_project\Walmart DataSet.csv"

## 📬 Contact

📧 Pavan Kumar — Data Analyst  
🔗 [LinkedIn](www.linkedin.com/in/pavan-kumar-152ba3245) | [GitHub](https://github.com/pavanreak)
