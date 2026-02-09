# 📊 Chicago Crime Rate Forecasting using Time Series Analysis

## 👋 About the Project
This project analyzes historical crime data from the city of Chicago to understand how crime patterns change over time and to forecast future crime trends.

The main goal of this work is to move beyond simple data exploration and use **time series analysis** to generate insights that can support **public safety planning, resource allocation, and policy decisions**.

The complete analysis was developed and executed using **Google Colab** and Python.

---

## 🎯 Problem Statement
Urban crime has a direct impact on citizens’ safety and city governance.  
To make informed decisions, city authorities need to understand:
- How crime evolves over time  
- Whether there are seasonal patterns  
- What future crime levels might look like  

This project addresses these questions using historical data and forecasting techniques.

---

## 🎯 Project Objectives
- Analyze long-term and seasonal crime trends in Chicago  
- Prepare raw crime data for time series analysis  
- Forecast future crime rates using a statistical forecasting model  
- Present insights through clear visualizations and documentation  

---

## 🗂 Dataset Information
- **Source:** Chicago Open Data Portal  
- **Type:** Historical crime incident records  
- **Granularity:** Individual crime events  
- **Time Coverage:** Multiple years  

> Note: The raw dataset is not included in this repository due to size constraints.

---

## 🧰 Tools & Technologies
- **Programming Language:** Python  
- **Environment:** Google Colab  
- **Libraries Used:**  
  - Pandas & NumPy for data processing  
  - Matplotlib & Seaborn for visualization  
  - Prophet for time series forecasting  

---

## 🔄 Project Workflow
1. Data loading and initial inspection  
2. Data cleaning and preprocessing  
3. Aggregation of crime records at monthly and yearly levels  
4. Exploratory Data Analysis (EDA)  
5. Time series forecasting using Prophet  
6. Visualization and interpretation of results  

---

## 📈 Key Visual Insights

### Yearly Crime Trend
This chart shows how total crime volume has changed over the years.
![Yearly Crime Trend](report/charts/yearly_crime_trend.png)

### Monthly Crime Pattern
Monthly aggregation reveals strong seasonal patterns in crime activity.
![Monthly Crime Trend](report/charts/monthly_crime_trend.png)

### Time Series Forecast
The Prophet model captures both trend and seasonality in the data.
![Monthly Forecast](report/charts/prophet_monthly_forecast.png)

### Five-Year Crime Forecast
This forecast provides a long-term view of expected crime trends.
![5 Year Forecast](report/charts/five_year_forecast.png)

---

## 🧠 Key Insights
- Crime data shows clear long-term trends and seasonal behavior  
- Monthly aggregation reduces noise and improves forecast stability  
- The forecasting model provides interpretable and practical results  
- Time series analysis can support proactive planning decisions  

---

## ⚠️ Limitations
- External factors such as policy changes or social events are not included  
- Forecasting is performed at an overall crime level, not by crime category  
- Model evaluation metrics can be added for deeper validation  

---

## 📄 Detailed Project Report
A complete visual analysis and explanation of the project is available here:

👉 **[View Full Project Report](report/Project_Report.md)**

---

## ▶️ How to Run This Project
1. Open the notebook in **Google Colab**
2. Mount Google Drive (if required)
3. Install dependencies from `requirements.txt`
4. Run the notebook cells sequentially

---

## 📓 Notebook
The full analysis notebook is available in this repository:

👉 **[Chicago Crime Forecasting Notebook](notebooks/chicago_crime_forecasting.ipynb)**

---

## 📌 Conclusion
This project demonstrates how time series analysis can transform historical crime data into meaningful future insights. By combining data cleaning, exploration, forecasting, and visualization, the analysis provides a clear example of how analytics can support real-world decision-making.

---

## 👩‍💻 Author
**Ragini Pawaiya**  
📧 Email: raginipawaiya5@gmail.com
🔗 LinkedIn : www.linkedin.com/in/ragini-pawaiya/

