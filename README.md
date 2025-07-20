# Project (Internship)
# 🛒 E-commerce Return Rate Reduction Analysis <br><br>

**📌 Overview**

This project focuses on analyzing and predicting product return behavior in an e-commerce setting. Using real-world data from the UCI Online Retail dataset, it aims to identify patterns behind high return rates and build a predictive model to assess return risk. The insights are visualized in an interactive Power BI dashboard.<br><br>

**🎯 Objectives**
- Analyze return behavior by product, region, and time.
- Predict probability of return using logistic regression.
- Identify high-risk products and orders for preemptive action.
- Build an interactive dashboard for stakeholders.<br><br>

**Tools**

| Tool                                               | Purpose                        |
| -------------------------------------------------- | ------------------------------ |
| Python (Pandas, scikit-learn, matplotlib, seaborn) | Data analysis and modeling     |
| SQLite                                             | Lightweight SQL querying       |
| Power BI                                           | Interactive dashboard creation |
| Jupyter Notebook                                   | Development environment        |
<br>

**🛠 Key Steps**

**1.Data Cleaning**
- Removed canceled and incomplete records
- Created derived features: `order_value`, `Month`, `return_flag`

**2.Exploratory Data Analysis (EDA)**
- Visualized return rates by country, product, and time
- Identified top-returned items and seasonal return trends

**3.SQL Analysis (SQLite)**
- Grouped return behavior by:
  - Product Category
  - Month
  - Country

**4.Logistic Regression Modeling**
- Trained a logistic regression model to predict return probability
- Generated a new column: `risk_score` (predicted return risk)

**5.Power BI Dashboard**
- Created KPIs:
  - Total returns
  - High-risk orders
  - Average return rate
- Visualizations:
  - Return risk by country, product, and month
  - Return trends over time
- Interactive table of high-risk orders with filters 

**📊 Deliverables**

 Cleaned dataset 

 High-risk predictions 

 Interactive dashboard <br><br>

**🏁 Conclusion**

This project demonstrates how predictive modeling and business intelligence can work together to tackle return management in e-commerce. With proactive insight into high-risk orders, companies can reduce return rates, optimize logistics, and improve customer experience. <br><br>

**Acknowledgements**

UCI ML Repository

Scikit-learn, Pandas, and the Python community

