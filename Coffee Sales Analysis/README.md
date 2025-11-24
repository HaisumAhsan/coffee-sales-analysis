**☕ Coffee Sales Analysis 

Data Visualization \| Exploratory Data Analysis \| Predictive Analytics**

A complete end-to-end data analytics project using the \*\*Coffee Sales
Dataset\*\* from Kaggle. The project includes data cleaning, EDA, visual
insights, machine learning models, forecasting, and a Power BI dashboard
for business decision-making.



**📦 Dataset 
Source:** Kaggle -- Coffee Sales Dataset  -

**Link:** https://www.kaggle.com/datasets/navjotkaushal/coffee-sales-dataset 

**Records:** 3,547

**Features:** 11 (Date, Time, Coffee Type,Money, Weekday, Month, etc.)

**Quality:** No missing or duplicate values


**🎯 Project Objectives**  - Analyze coffee shop sales trends  -
Identify top-selling products  - Understand hourly, daily, monthly
revenue patterns  - Compare store performance  - Build ML models to
forecast revenue  - Create a BI dashboard for business insights

\-\--

\## **📊 Exploratory Data Analysis (EDA)**

\### ✔ Data Overview  - Checked column names, datatypes, and record
count  - Validated dataset had \*\*no missing or null entries\*\*  -
Converted and extracted features from the date column

\### ✔ Sales Behavior  - Sales distribution by coffee type  - Daily,
weekly & monthly sales trends  - Quantity and revenue relationships  -
Customer buying patterns

\### ✔ Key Insight Some coffee types consistently dominate both
\*\*sales count\*\* and \*\*total revenue\*\*, making them ideal for
focused marketing and stock optimization.

\-\--

\## 📈 Visual Insights

\### Product Performance  - Bar/Count plots of top-selling coffee types
 - Revenue by coffee category  - Highest revenue-generating varieties

\### Time-Based Trends  - Hourly sales spikes (morning & lunch peaks)  -
Daily/Monthly revenue patterns  - Store-wise sales comparison

\### Correlation  - Heatmap showing strong correlation between
\*\*quantity sold\*\* and \*\*revenue\*\*

\-\--

\## 🤖 Machine Learning Models

\| Model \| MAE ↓ \| RMSE ↓ \| R² ↑ \| Notes \|
\|\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--\|\-\-\-\-\-\--\|\-\-\-\-\-\-\--\|\-\-\-\-\-\--\|\-\-\-\-\-\--\|
\| Linear Regression \| 3.19 \| 4.09 \| 0.27 \| Baseline model;
underfits \| \| Random Forest \| 0.26 \| 0.69 \| 0.979 \| Excellent
performance \| \| XGBoost \| 0.34 \| 0.79 \| 0.973 \| Strong but
slightly lower \| \| CatBoost \| 0.33 \| 0.66 \| 0.981 \| \*\*Best model
overall\*\* \|

\*\*CatBoost\*\* is chosen as the final model due to high accuracy and
lowest error.

\-\--

\## 🔮 Forecasting (Holt--Winters Model)  - Forecasted 30-day revenue
for March 2025  - Captures seasonality and trend patterns accurately  -
Expected daily revenue: \*\*350--600 units\*\*  - Revenue remains stable
with regular fluctuations

\-\--

\## 🧠 Strategic Recommendations

\### Product Strategy  - Focus marketing on top 3 high-revenue coffee
types  - Promote premium coffees (high margin)

\### Operations  - Increase staff & inventory during morning/lunch peaks
 - Benchmark top-performing store locations

\### Forecasting  - Use CatBoost for ongoing sales prediction  - Use
Holt--Winters for seasonal demand planning

\### Business Insights  - Stable revenue indicates mature customer base
 - Data supports robust inventory and staffing decisions

\-\--

\## 📁 Project Structure
