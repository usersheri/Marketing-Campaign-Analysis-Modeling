<img width="2324" height="1326" alt="image" src="https://github.com/user-attachments/assets/4eb3e263-f945-459b-8433-d572f4c830d9" />


📊 Marketing Campaign Performance Analysis & Conversion Prediction

🚀 Project Summary

This project analyzes multi-channel marketing campaign data to uncover key drivers of customer conversion and build a predictive model to estimate campaign success.

It combines data analysis, visualization, and machine learning to provide actionable insights for marketing optimization.

🎯 Business Objective

Identify which factors influence conversions
Compare performance across marketing channels
Optimize marketing spend allocation
Predict likelihood of conversion using historical data

📂 Dataset Features

Spend – Budget allocated per campaign
Duration – Campaign runtime
Clicks & Impressions – Engagement metrics
CTR (Click-Through Rate) – Engagement efficiency
CPC (Cost Per Click) – Cost efficiency
Channel – Marketing platform
Conversion – Target variable

🧹 Data Preparation

Removed duplicate columns (e.g., repeated Clicks)
Corrected data types for accurate analysis
Handled missing values
Standardized dataset structure
Verified data consistency

📊 Exploratory Data Analysis

Key findings from EDA:

Channel performance varies significantly
Higher CTR tends to correlate with conversions
Increasing spend does not always increase ROI
Some channels are more cost-efficient than others

⚙️ Feature Engineering

Applied One-Hot Encoding for categorical variable (Channel)
Selected relevant numerical and encoded features
Built a structured dataset ready for modeling

🤖 Machine Learning Model

Model Used:
Lasso Regression (L1 Regularization)
Why this model?
Automatically performs feature selection
Reduces overfitting
Improves model interpretability

📈 Model Evaluation

R² Score – Measures model performance
Mean Squared Error (MSE) – Error metric
Coefficient Analysis – Identifies impactful features

📊 Dashboard (Power BI)

Developed an interactive dashboard with:

Conversion Rate KPIs
Channel-wise performance comparison
Spend vs Conversion analysis
Marketing funnel:
Impressions → Clicks → Conversions

💡 Key Insights

High CTR campaigns are more likely to convert
Certain channels outperform others consistently
Cost efficiency (CPC) plays a critical role
Data-driven budgeting can improve ROI

🛠️ Tech Stack

Python (Pandas, NumPy, Scikit-learn)
Data Visualization (Matplotlib, Seaborn)
Power BI
Jupyter Notebook

📁 Project Structure

├── data/              # Raw & cleaned datasets
├── notebooks/         # Analysis & modeling
├── dashboard/         # Power BI files
├── models/            # Saved models
├── README.md

🌟 What Makes This Project Stand Out

End-to-end workflow: Data Cleaning → EDA → ML → Dashboard
Combines analytics + business understanding
Focus on real-world marketing optimization
Clear, interpretable model (Lasso Regression)

🔮 Future Enhancements

Implement advanced models (Random Forest, XGBoost)
Perform hyperparameter tuning
Add cross-validation
Deploy model using Flask / FastAPI
Integrate real-time data pipeline

👤 Author

FATHIMA NIHALA
