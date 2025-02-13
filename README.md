**Predicting Purchase Behavior & Cart Abandonment Analysis**

📌 **Overview**

This project focuses on predicting customer purchases using machine learning models, analyzing feature importance, and developing an interactive Power BI dashboard. By leveraging demographic data (country, device, time, and day of the week), this project aims to optimize e-commerce decision-making and reduce cart abandonment.

📊 **Key Components**

1️⃣ **Machine Learning Model**

Model Type: Hybrid Model (65% XGBoost, 35% Random Forest, Threshold = 0.48)

Purpose: Predict whether a user will complete a purchase based on available demographic data.

Performance Metrics:

Accuracy: 96.42%

Precision (Purchases): 0.14

Recall (Purchases): 0.15

False Positives: Low

False Negatives: Moderate

2️⃣ **Feature Importance Analysis**

Most Influential Factors:
1️⃣ Country (strongest predictor of purchase likelihood)
2️⃣ Hour of the Day (certain time windows show higher conversion rates)
3️⃣ Day of the Week (weekend vs. weekday trends)
4️⃣ Device Type (had the least impact on purchasing decisions)

3️⃣ **Power BI Interactive Dashboard**

Conversion Funnel Visualization: Shows user journey from site visit → cart → purchase.

Interactive Filters: Explore conversion rates by country, device, and time of day.

KPI Metrics: Real-time tracking of cart abandonment rate and conversion rate.

Geographic Analysis: Bubble map displaying purchase likelihood by region.

**🚀 Getting Started**

1️⃣ **Clone the Repository**

git clone https://github.com/yourusername/ecommerce-purchase-prediction.git
cd ecommerce-purchase-prediction

2️⃣ **Install Dependencies**

pip install -r requirements.txt

3️⃣ **Run the Machine Learning Model**

python scripts/train_model.py

4️⃣ **Open the Power BI Dashboard**

Open Power BI Desktop.

Import the .pbix file from the powerbi folder.

Explore the conversion trends & cart abandonment analysis.

📈 **Relevant Insights & Next Steps**

🔹 **Key Insights**

✅ Country is the most significant factor in purchase behavior.
✅ Time of day & day of the week influence conversions—targeted campaigns can be optimized.
✅ Device type has minimal impact, meaning responsive design isn’t a major barrier.
✅ Cart abandonment remains a major issue, highlighting opportunities for re-engagement campaigns.

🔜 **Next Steps**

📌 Enhance feature engineering by incorporating session duration, product category, and user intent signals.
📌 Implement real-time predictions using a deployed API to suggest promotions dynamically.
📌 Optimize marketing campaigns by running A/B tests based on high-converting time windows.

**🚀 This project serves as a foundation for data-driven e-commerce optimization!**
