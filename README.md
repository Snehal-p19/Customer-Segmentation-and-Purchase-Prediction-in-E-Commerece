# 🛍️ Customer Segmentation and Purchase Prediction in E-commerce

This project focuses on segmenting e-commerce customers based on their behavior and demographics, and predicting the likelihood of future purchases using machine learning models. It provides insights that can help improve marketing strategies and customer targeting.

---

## 📌 Objective

- Segment customers into meaningful groups based on their attributes and behaviors
- Predict whether a customer is likely to make a purchase
- Help businesses tailor personalized marketing and product recommendations

---

## 📊 Dataset

- **Data Source**: [Insert source if available – Kaggle or synthetic]
- Contains fields such as:
  - `CustomerID`
  - `Age`, `Gender`, `Annual Income`, `Spending Score`
  - `PurchaseHistory`, `BrowsingTime`, `IsPurchased`

---

## 🛠️ Tools & Libraries

- Python 🐍
- Pandas & NumPy – Data wrangling
- Matplotlib & Seaborn – Data visualization
- Scikit-learn – Clustering & prediction
- XGBoost / RandomForest – Classification model
- Plotly (optional) – Interactive visualizations

---

## 📈 Project Workflow

1. **Data Preprocessing**  
   - Handling missing values and outliers  
   - Feature engineering (e.g., average spend, time on site)  
   - Encoding categorical variables  

2. **Exploratory Data Analysis (EDA)**  
   - Visualizing distribution of key features  
   - Correlation analysis  

3. **Customer Segmentation**  
   - Used KMeans clustering to group customers into segments  
   - Evaluated optimal clusters using Elbow Method and Silhouette Score  

4. **Purchase Prediction**  
   - Modeled customer likelihood to purchase (target: `IsPurchased`)  
   - Trained and evaluated Logistic Regression, Random Forest, and XGBoost  
   - Assessed models with accuracy, precision, recall, and ROC-AUC  

---

## 🔍 Key Findings

- Identified 3–5 unique customer segments based on income and behavior
- High-income, high-engagement customers had the highest purchase likelihood
- Random Forest model achieved the best balance of precision and recall

