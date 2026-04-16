# 📊 Education Spending vs Literacy Analysis (India)

🚀 A complete data analysis and machine learning project exploring how **education spending and population influence literacy rates across Indian states**.

---

## 📌 Overview

This project investigates whether higher education spending actually leads to better literacy outcomes. Using real-world datasets, I performed:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Statistical Testing (t-test)
* Machine Learning (Linear Regression)

👉 The goal was not just to build a model, but to **understand the story behind the data**.

---

## 💭 Motivation

This project was not straightforward.

* Struggled to find reliable datasets
* Faced issues with inconsistent formats
* Lost track multiple times during preprocessing

Instead of giving up, I focused on solving one problem at a time — and that’s how this project came together.

---

## 📂 Project Structure

```
education-literacy-analysis/
│
├── data/           # Raw datasets
├── notebook/       # Jupyter Notebook (analysis)
├── visuals/        # Graphs & outputs
├── reports/        # Final report
└── README.md
```

---

## 📊 Exploratory Data Analysis

### 📈 Literacy Trend

* Literacy shows a **consistent upward trend** over time

### 💰 Spending vs Literacy

* No strong visible relationship
* Spending is constant across states per year → limits insight

### 👥 Population vs Literacy

* Weak relationship
* Literacy varies regardless of population size

### 📦 Distribution Analysis

* Most literacy values lie between **75–85**
* Slight skewness with a few high-performing states

---

## 🔥 Key Visualizations

### Correlation Heatmap

![Heatmap](visuals/your_heatmap.png)

### Spending vs Literacy

![Scatter](visuals/your_scatter.png)

### Distribution Plot

![Histogram](visuals/your_hist.png)

> 📌 *(Replace image names with your actual files in `/visuals` folder)*

---

## 🧠 Key Insights

* 📈 Literacy is improving over time
* 💰 Education spending alone does not strongly explain literacy
* 👥 Population has weak influence
* ⚖️ Per capita spending is more meaningful
* 🧩 Literacy depends on multiple socio-economic factors

---

## 📊 Statistical Analysis (t-test)

A t-test was performed to compare literacy rates between:

* High spending group
* Low spending group

📌 Result:

> No statistically significant difference found

👉 This suggests that **higher spending alone does not guarantee better literacy outcomes**.

---

## 🤖 Machine Learning Model

### Model Used:

* Linear Regression

### Features:

* Year
* Spending
* Population
* Per Capita Spending

### Evaluation:

* Mean Squared Error (MSE)
* R² Score

📌 Result:

* Model shows **moderate performance**
* Captures general trend but not highly accurate

---

## ⚠️ Limitations

* Spending data is not state-wise
* Limited features available
* Missing socio-economic variables
* Weak correlations affect prediction strength

---

## 🚀 Future Improvements

* Add more features (GDP, education quality, infrastructure)
* Use advanced models (Random Forest, XGBoost)
* Build interactive dashboard (Streamlit)

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 💡 Key Takeaway

> “Weak correlation doesn’t mean failure — it means deeper insight.”

This project taught me that real-world data is complex, and understanding **why results behave a certain way** is more important than just getting high accuracy.

---

## 🙌 Connect With Me

If you found this interesting or have suggestions, feel free to connect or share feedback!

---

⭐ If you like this project, consider giving it a star!
