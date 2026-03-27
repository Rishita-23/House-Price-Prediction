# 🏡 Housing Price Prediction & EDA

---

## ✨ Overview

This project explores a housing dataset through **Exploratory Data Analysis (EDA)** and builds **machine learning models** to predict house prices.

From raw data → insights → feature engineering → modeling — this notebook walks through a complete **end-to-end data science workflow**.

---

## 🚀 Key Highlights

* 📊 In-depth **Exploratory Data Analysis**
* 🧹 Handling **missing values**
* 🔍 Correlation & feature importance analysis
* ⚙️ Custom **feature engineering**
* 🤖 Model building with:

  * Linear Regression
  * Random Forest Regressor
* 📈 Performance evaluation using RMSE, MAE & R²

---

## 📂 Dataset

* Housing dataset (`housing.csv`)
* Contains features like:

  * Median income
  * Location (latitude & longitude)
  * Number of rooms, bedrooms
  * Population & households

---

## 🔎 Exploratory Data Analysis

### ✔️ Initial Exploration

* Dataset shape, structure, and summary statistics
* Identification of missing values

### ✔️ Visualizations

* Histograms for feature distributions
* Geographical scatter plots (price vs location)
* Correlation heatmap

### 📌 Key Insights

* 💰 **Median income** strongly influences house prices
* 📍 Location plays a major role in pricing
* 🏘️ Housing density features add valuable context

---

## 🧠 Feature Engineering

New features created to improve model performance:

* `rooms_per_household`
* `bedrooms_per_household`
* `population_per_household`

These help capture **real-world relationships** in the data.

---

## ⚙️ Data Preprocessing

Using `scikit-learn` pipelines:

* 🧩 Missing value imputation
* 🔢 Feature scaling
* 🔤 One-hot encoding for categorical data
* 🔗 ColumnTransformer for clean workflow

---

## 🤖 Models Used

### 1. Linear Regression

* Simple baseline model
* Assumes linear relationships

### 2. Random Forest Regressor 🌳

* Ensemble learning method
* Captures **non-linear patterns**
* More robust and accurate

---

## 📊 Model Evaluation

Metrics used:

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* R² Score

### 🏆 Results

* Random Forest outperformed Linear Regression
* Better at handling complex relationships in data

---

## 💡 Insights & Learnings

* Real-world data is rarely linear
* Feature engineering significantly improves performance
* Ensemble models often outperform simple models
* Visualization is key to understanding data

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/housing-price-prediction.git

# Navigate to project folder
cd housing-price-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```

---

## 📈 Future Improvements

* 🔍 Hyperparameter tuning
* 🚀 Try advanced models (XGBoost, Gradient Boosting)
* 🌐 Deploy as a web app
* 📊 Add interactive dashboards

---

## 🤝 Contributing

Pull requests are welcome!
If you find a bug or have suggestions, feel free to open an issue.

---

## ⭐ Show Some Love

If you liked this project, give it a ⭐ on GitHub!

---

> *Data is powerful. But insight? That’s where the magic happens.* ✨
