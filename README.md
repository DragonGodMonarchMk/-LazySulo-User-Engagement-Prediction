# -LazySulo-User-Engagement-Prediction
This project builds a predictive model for **user engagement levels** in the LazySulo app, leveraging historical customer data and app usage patterns.   The aim is to help the business **forecast engagement trends**, identify at-risk users, and design
LazySulo User Engagement Prediction — A machine learning project to predict user engagement levels for a mobile application using historical usage and customer data. This project applies time-series and tabular modeling techniques, feature engineering, and evaluation to achieve a RMSE score of 2.57, enabling actionable insights to improve app retention and engagement strategies.
# 📱 LazySulo – User Engagement Prediction

## 📌 Project Overview
This project builds a predictive model for **user engagement levels** in the LazySulo app, leveraging historical customer data and app usage patterns.  
The aim is to help the business **forecast engagement trends**, identify at-risk users, and design targeted strategies for retention.

The solution combines **time-series analysis** with **regression modeling**, achieving a **2.57 RMSE score**.

---

## 📊 Dataset Overview
The project uses two primary datasets:

### `customers.csv`
- User demographics & profile data
- Example features:
  - `customer_id` – Unique user ID
  - `age`, `gender` – Demographic details
  - `registration_date` – Date user joined
  - `location` – User location/region

### `test.csv`
- User engagement data for model evaluation
- Used for **final prediction submission**

---

## 📈 Key Analysis & Modeling Steps
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Time-series feature extraction

2. **Exploratory Data Analysis (EDA)**
   - Usage trends over time
   - Seasonal patterns in engagement
   - Demographic engagement differences

3. **Feature Engineering**
   - Aggregating historical usage metrics
   - Creating lag features for temporal dependencies
   - Normalizing continuous variables

4. **Modeling**
   - Regression models (e.g., LightGBM, XGBoost, CatBoost)
   - Cross-validation for robust performance
   - RMSE score optimization

5. **Evaluation**
   - Final RMSE: **2.57**
   - Feature importance analysis

---

## 🔍 Tools & Technologies
- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, LightGBM, XGBoost, matplotlib, seaborn
- **Notebook:** Jupyter Notebook

---

## 📌 Key Insights
- Engagement is **strongly influenced** by recent app usage trends.
- Demographic factors like **age group and region** correlate with engagement.
- Seasonal variations (e.g., weekends, holidays) play a major role in activity spikes.
- Combining **time-series features** with static customer attributes improved accuracy.

---

## 🚀 Potential Applications
- Predict churn risk for **proactive retention campaigns**.
- Segment users for **personalized marketing**.
- Allocate resources (e.g., server load balancing) based on predicted engagement peaks.

---

## 📂 Repository Structure

📁 LazySulo-User-Engagement-Prediction
│── 📄 lazysulo-user-engagement-pred-2-57-rmse-score.ipynb # Main prediction notebook
│── 📄 customers.csv # Customer profile dataset
│── 📄 test.csv # Test set for predictions
│── 📄 customers-app-usage-no-dl-multi-timeseries.ipynb # Time-series analysis notebook
│── 📄 README.md # Project documentation


---

## 📜 License
This project is for educational and analytical purposes. Datasets are proprietary and used for demonstration.

---

## ✍ Author
**Manish**  
GitHub: [DragonGodMonarchMk](https://github.com/DragonGodMonarchMk)

Edit

