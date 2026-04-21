# 🏠 Housing Price Prediction

A machine learning project that predicts house sale prices based on features like size, location, and quality.

---

## 📋 Overview

Using the Ames Housing Dataset, this project builds a model that can predict the price of a house within ~$17,000 of the actual sale price.

This was built as a beginner machine learning project to learn the basics of data science, including data cleaning, exploratory data analysis, and model training.

---

## 📁 Project Structure

```
housing-prediction/
│
├── data/
│   ├── train.csv         # Training data
│   └── test.csv          # Test data
│
├── notebooks/
│   └── eda.ipynb         # Main notebook (EDA + model)
│
├── requirements.txt      # Dependencies
└── README.md
```

---

## 🔧 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/yourusername/housing-prediction.git
cd housing-prediction
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Download the dataset**

Download `train.csv` and `test.csv` from [Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) and place them in the `data/` folder.

**4. Open the notebook**
```bash
jupyter notebook
```

Then open `notebooks/eda.ipynb` and run all cells.

---

## 📊 Results

| Model | Average Prediction Error |
|---|---|
| Linear Regression | ~$825,000 (too high) |
| Random Forest | **~$17,600** ✅ |

The Random Forest model predicts house prices within approximately **$17,600** of the actual sale price, which is roughly 10% of the average house price of $180,000.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** — data loading and cleaning
- **Seaborn / Matplotlib** — data visualization
- **Scikit-learn** — machine learning model

---

## 📚 Dataset

[Ames Housing Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) from Kaggle. Contains 1,460 houses with 79 features each.

---

## 👤 Author

Your Name — [GitHub](https://github.com/thebossnoor)