# SwiftChain-Analytics-Project

Company Overview
SwiftChain Analytics is a global leader in logistics analytics, founded in 2010 and headquartered in Chicago. The company empowers businesses with machine learning-driven solutions for challenges like delivery delays, inventory bottlenecks, and transportation optimization. In 2024, SwiftChain launched a project to develop a predictive model for delivery delay classification, helping improve customer satisfaction and operational efficiency.

🎯 Project Objective
Develop a classification model to predict the delivery status of orders:

-1: Late delivery

0: On-time delivery

1: Early delivery

Key goals include:

Analyzing logistics data for trends and patterns

Preprocessing and engineering relevant features

Building and tuning machine learning models

Providing insights to reduce delivery delays

📁 About the Dataset
Files:

logistics.csv: Main dataset with 41 columns

feature_description.csv: Data dictionary

Categories Covered:
Customer demographics

Order details

Product and shipping information

Delivery outcomes (target variable: label)

Example Columns:
Column Name	Description
payment_type	Payment method used
sales_per_customer	Total sales per customer
shipping_mode	Shipping method used
order_date	Date the order was placed
shipping_date	Date the order was shipped
label	Delivery status: -1 (late), 0 (on-time), 1 (early)

🔍 Project Phases
📘 Phase 1: Understanding the Problem
Discuss the business impact of delivery delays

Analyze critical dataset variables

📊 Phase 2: Exploratory Data Analysis (EDA)
Inspect structure and summary statistics

Visualize key relationships (e.g., shipping mode vs. delay)

Handle missing values

⚙️ Phase 3: Data Preprocessing
Encode categorical variables (e.g., customer_segment, shipping_mode)

Handle outliers and missing data

Normalize numerical fields (e.g., profit_per_order)

🧠 Phase 4: Feature Engineering
Create features like shipping_duration

Engineer new variables from category and location fields

Perform feature selection

🤖 Phase 5: Model Development
Split data into training and testing sets

Train classifiers (e.g., Logistic Regression, Random Forest, XGBoost)

Tune best model using hyperparameter optimization

Evaluate using Accuracy and F1 Score

📈 Phase 6: Insights & Recommendations
Analyze top features influencing delivery delays

Provide actionable insights to minimize future delays

🛠️ Tools & Libraries
Python (Pandas, NumPy)

Scikit-learn

XGBoost / LightGBM

Matplotlib / Seaborn

✅ Status
Model successfully developed and evaluated. Insights and recommendations were generated to support SwiftChain’s goal of optimizing delivery performance and reducing delays across logistics networks.
