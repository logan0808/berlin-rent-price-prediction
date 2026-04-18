# 🏙️ Berlin Apartment Rental Price Prediction

**End-to-end regression project** predicting monthly rental prices in Berlin using machine learning (Random Forest R² = 0.8747).

*Completed: April 2026*

## Project Author

**Developed by:** Shehu Olakunle Yunus  
**GitHub:** [@logan0808](https://github.com/logan0808)  
**Repository:** [Berlin Rental Price Prediction](https://github.com/logan0808/berlin-rent-price-prediction)
---

## 📌 Overview
This project predicts rental prices in Berlin using property features and machine learning models.

---

## 🧰 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## ⚙️ Workflow
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis  
3. Feature Engineering  
4. Model Training  
5. Model Evaluation  

---

## 📊 Results
- Linear Regression → R²: 0.9861  
- Random Forest → R²: 0.9848  

## 📊 Model Output   

### Actual vs Predicted Prices
![Actual vs Predicted](Actual_vs_Predicted.png)

### Feature Importance Analysis

#### With Base Rent Included
![Feature Importance 1](Feature_importance_1.png)

#### Without Base Rent (Better Insight)
![Feature Importance 2](Feature_importance_2.png)

### 🔍 Interpretation

- The first plot shows that base rent dominates the prediction.
- After removing base rent, other features like living space and heating costs become more visible.
- This helps better understand secondary factors influencing rental prices.

## 🔍 Insights
- The model shows strong predictive performance...
---

## 🔑 Key Insights
- Base rent is the strongest predictor  
- Living space significantly impacts rent  
- Other features have smaller influence

## ⚠️ Limitations
While the model performs well, there are some limitations to consider:

- Model heavily depends on base rent, which is a direct component of total rent  
- External factors like location quality and market trends are not included  
- Dataset may not reflect real-time Berlin housing market dynamics

## 🚀 Future Improvements

- Include location-based features (district-level pricing)
- Experiment with advanced models (XGBoost, Gradient Boosting)
- Deploy as an interactive web app (Streamlit)

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
