# 🛍️ Customer Spending Analysis with Linear Regression

This project explores customer behavior data from an e-commerce company to understand what factors drive spending. Using linear regression, the goal is to determine whether the company should invest more in improving its **mobile app** or its **website** to boost customer revenue.

---

## 🔍 What the Data Tells Us

The dataset includes:
- Average Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent (Target)

### Key Insights:
- 📱 **Time on App** strongly correlates with increased customer spending.
- 🧾 **Length of Membership** is the most significant overall predictor.
- 🌐 **Time on Website** has minimal impact on spending.

These insights raise a business question:
> Should the company improve the website to catch up, or invest more in the app that’s already performing well?

Before acting, it would be helpful to explore how **Length of Membership** interacts with app and website usage to better understand long-term user behavior.

---

## 🛠 Tools Used

- Python
- Jupyter Notebook
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

---

## 📈 Techniques Applied

- Exploratory Data Analysis (EDA)
- Data visualization (pairplots, heatmaps, regression plots)
- Linear Regression Modeling
- Model evaluation (MAE, MSE, RMSE)
- Business-focused interpretation of regression coefficients

---

## 🚀 How to Run

1. Clone this repository
2. Install the required libraries
3. Open the notebook in Jupyter and run all cells

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
