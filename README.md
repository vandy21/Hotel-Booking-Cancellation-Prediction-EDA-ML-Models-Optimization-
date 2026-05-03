# 🏨 Hotel Booking Cancellation Prediction

## 🚀 Project Overview
This project focuses on analyzing hotel booking data and building machine learning models to **predict booking cancellations**.

The objective is to help businesses:
- Reduce revenue loss due to cancellations
- Improve customer targeting strategies
- Optimize pricing and booking policies

---

## 👨‍💻 Author
**RudraX HealthTech**

This project demonstrates my practical application of data science and machine learning to solve real-world business problems.

---

## 📊 Dataset Overview
- Total Records: **25,000+ bookings**
- Target Variable: `booking_status` (Cancelled / Not Cancelled)

### Key Features:
- Lead time (days before check-in)
- Average price per room
- Market segment (Online, Offline, Corporate)
- Number of adults / children
- Special requests
- Previous cancellations
- Room type & meal plan
- Seasonal factors

---

## 🔍 Exploratory Data Analysis (EDA)

### Key Insights:

- 📉 **32.78% bookings are cancelled**
- 🌐 **Online segment dominates (63.99%)**
- 💰 Higher prices → Higher cancellation probability  
- ⏳ Longer lead time → More cancellations  
- ⭐ Special requests reduce cancellations significantly  
- 🔁 Repeat customers have very low cancellation rate (~1.7%)  

---

## ⚙️ Data Preprocessing

- No missing values (clean dataset)
- Outlier treatment using transformation & clipping  
- Feature engineering (binning & encoding)  
- Train-test split with balanced distribution  

---

## 🤖 Models Implemented

### 1. Naive Bayes
- ❌ Low performance (~40% accuracy)
- High precision but very low recall

---

### 2. K-Nearest Neighbors (KNN)

#### Best Model: **K = 9**
- ✅ Training Accuracy: ~87%
- ✅ Test Accuracy: ~84%
- ✅ Strong Precision & Recall (~88%)

👉 **Best performing model overall**

---

### 3. Logistic Regression

- Accuracy: ~80%
- ROC-AUC: **0.86**
- Good balance between precision & recall

#### Optimization:
- Threshold tuning (0.55 / 0.66)
- Multicollinearity handling (VIF)
- Feature selection using p-values

---

## 📊 Model Comparison

| Model              | Accuracy | Performance |
|------------------|---------|------------|
| Naive Bayes       | ~40%    | Poor       |
| Logistic Regression | ~80%  | Good       |
| KNN (K=9)         | ~84%    | Best ✅     |

---

## 📈 Key Business Insights

- 📊 Online bookings are more price-sensitive  
- ⏳ Long lead-time bookings are high-risk  
- 💰 Expensive rooms → higher cancellation probability  
- ⭐ More special requests → lower cancellations  
- 🔁 Repeat customers are highly reliable  

---

## 💡 Business Recommendations

- Offer incentives for early commitment bookings  
- Focus on repeat customer retention  
- Adjust pricing dynamically for online segment  
- Encourage special requests/customization  
- Monitor high-risk bookings (long lead time + high price)  

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels

---

## 📈 Future Improvements

- Implement XGBoost / Random Forest  
- Deploy model as API or dashboard  
- Real-time cancellation prediction system  
- Integrate with booking platforms  

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork and improve the project.

---

## 📬 Contact
For collaboration or business use-cases, connect via GitHub.
