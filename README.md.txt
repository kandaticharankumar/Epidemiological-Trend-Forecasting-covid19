# Epidemiological (COVID-19) Trend Forecasting & Time-Series Visual Analytics

An end-to-end data analytics and time-series modeling project exploring global infection spreads and generating 7-day forward forecasts with statistical confidence intervals.

## Features
- **Data Preprocessing & Aggregation:** Cleaned multi-national case records (`covid_19_clean_complete.csv`), analyzed state-level granularities for China, and isolated active/recovered/death metrics across 187+ countries.
- **Exploratory Visual Analytics:** Plotted daily global confirmed trajectory curves, top 10 active case distribution rankings, and multi-country trajectory trends (India vs. US vs. China) using **Matplotlib** and **Seaborn**.
- **Time-Series Forecasting:** Built an additive forecast pipeline using **Facebook Prophet** to forecast 7 days forward along with 95% upper and lower statistical confidence intervals.
