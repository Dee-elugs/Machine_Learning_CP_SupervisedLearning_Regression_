# ⚡ 5G Energy Consumption Prediction Using Supervised Regression

A hands-on machine learning regression project that predicts energy consumption of 5G base stations based on network usage metrics. Built using Python and trained on real-world telecom data.

💻 Developed using Jupyter Notebook

---

## 🎯 Objective

This project is designed to help learners and practitioners:

- Apply regression techniques on real-life energy consumption data.
- Understand how network features like load, transmission power, and energy-saving modes impact energy usage.
- Evaluate machine learning models using robust metrics like MAE, RMSE, and R².
- Gain practical experience in data preprocessing, feature selection, and model deployment.

---

## 📦 What's Included

The notebook walks through a complete ML workflow including:

- 📥 **Data Loading & Exploration**
  - Dataset: `5G_energy_consumption_dataset.csv`
  - 92,629 rows × 6 columns
  - Clean data (no nulls or duplicates)
  - Label encoding used for categorical values

- 🧹 **Data Preparation**
  - Feature Selection: `BS`, `load`, `ESMODE`, `TXpower`
  - Target: `Energy`
  - Train-test split: 80/20

- 🤖 **Model Building**
  - Model: `RandomForestRegressor` from `sklearn`
  - Training and prediction pipeline

- 📊 **Evaluation Metrics**
  - MAE: `2.03`
  - RMSE: `3.21`
  - R² Score: `0.95`

---

## 🛠 Tech Stack

- **Language:** Python 3.x  
- **Notebook Environment:** Jupyter  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn

---

## 💡 Learning Experience

This project helped me reinforce my knowledge of supervised regression through a real-world application. From understanding the data to training a highly accurate model, each step improved my skills in:

- Data cleaning and feature engineering  
- Model development and evaluation  
- Performance interpretation using industry metrics  

---

## 🤝 Contributions

Pull requests and suggestions are welcome!  
If you'd like to add other models, refactor code, or enhance visualizations, feel free to fork the repo and contribute.

---

## 🙌 Acknowledgments

Special thanks to the open-source ML and data science community for consistent guidance, code examples, and shared datasets.

---

## 🔗 Links

👉 [View Notebook on GitHub](https://github.com/Dee-elugs/Machine_Learning_CP_SupervisedLearning_Regression_/blob/main/Machine_Learning_Supervised_Regression_CP1.ipynb)
"""
