# House-Price-Prediction

📌 Project Overview

This project focuses on predicting house sale prices in Ames, Iowa, using a real-world dataset. The core emphasis is on Automated Machine Learning (AutoML) to speed up the end-to-end workflow—from Exploratory Data Analysis (EDA) to feature engineering and model deployment.

🏢 Business Problem

Traditional property valuation is time-consuming and often subjective. This project aims to provide a data-driven system that delivers instant and objective price estimates, helping real estate companies optimize their pricing strategies and reduce manual appraisal effort.

🛠️ Automated Workflow

I utilized several cutting-edge automation tools to enhance productivity:

Automated EDA: Used YData-Profiling to instantly generate comprehensive data insights and identify correlations.
Automated Feature Engineering: Leveraged Featuretools and AutoFeat to create complex new features (like Property Age and interaction terms) without manual coding.
Automated Modeling: Employed PyCaret to benchmark 15+ algorithms simultaneously. Gradient Boosting Regressor was identified as the top performer.
📊 Key Results

The final model achieved a high level of precision, making it suitable for real-world business applications:

R² Score: 0.9256 (Explains 92% of the price variance).
Mean Absolute Error (MAE): ~$15,214.
MAPE (Average Error %): 8.4%.
💡 Business Insights

Quality is King: OverallQual is the most significant driver of price. High-quality construction commands a premium regardless of size.
Location Premium: Neighborhood emerged as a top predictor, often outweighing house size in influence.
Property Age: Automated features revealed that recently remodeled or newer homes have a much higher market liquidity and value.
