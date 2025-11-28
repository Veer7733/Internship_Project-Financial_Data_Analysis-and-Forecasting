# Internship_Project-Financial_Data_Analysis-and-Forecasting
Analyze tesla's stock data and forecasting using ARIMA model also preparing dashboard.

---

## Project Overview
This project focuses on analyzing financial datasets and building forecasting models to predict future performance. It leverages **Power BI for interactive dashboard development** and **Python for data analysis and time-series forecasting**.

---

## Objective
- Analyze financial data (stock prices, financial metrics, market trends).
- Identify historical trends through visualizations and EDA.
- Build predictive models to forecast future financial performance.
- Present results using an interactive Power BI dashboard.
- Provide business insights for decision-making, investment strategies, and cost optimization.

---

## Dashboard Preview
![Dashboard Preview](https://github.com/Veer7733/Internship_Project-Financial_Data_Analysis-and-Forecasting/blob/main/Dashboard/Stock%20Analysis%20and%20Forecasting%20Dashboard_Preview.png)

---

## Tools & Technologies

| Category | Tools Used |
|----------|------------|
| **Data Visualization** | Power BI |
| **Programming Language** | Python |
| **Python Libraries** | Pandas, NumPy, Matplotlib, **Seaborn**, **Statsmodels**, **scikit-learn** |
| **Forecasting Techniques** | ARIMA (Autoregressive Integrated Moving Average) |
| **IDE/Notebook** | Jupyter Notebook |
| **Version Control** | Git & GitHub |

---

## Workflow & Methodology

### 1. Data Cleaning
- Handled missing values and outliers in raw financial data  
- Converted date fields to proper datetime format  
- Normalized metrics 
- Prepared data for time-series modeling (stationarity, auto-correlation and partial auto-correlation, differencing/integration )

### 2. Exploratory Data Analysis (EDA)
- Analyzed stock price trends and other key financial indicators  
- Assessed growth patterns and volatility

### 3. Visualization (Power BI)
- Stock price trend analysis (Line chart)
- Predicted v/s Actual adjusted closing price analysis (Scatter plot)
- Monthly and Yearly high and low of stock price (Area chart)
- Interactive KPI tracking with filters (time-period, metrics, comparison)

### 4. Forecasting (Python)
- Time-series techniques: **ARIMA**
- Forecasting using regression / ML (via **scikit-learn**, if required)  
- Model performance evaluation using **MAE**, **RMSE**   

### 5. Insights & Interpretation
- Assessed overall financial health  
- Derived forecast-based recommendations  
- Suggested strategic actions (investment, growth opportunities, cost control)

---

##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Veer7733/Internship_Project-Financial_Data_Analysis-and-Forecasting
   ``` 
2. Navigate to the project folder:
   ```bash
   cd Internship_Project-Financial_Data_Analysis-and-Forecasting
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Financial Data Analysis and Forecasting.ipynb
   ```
