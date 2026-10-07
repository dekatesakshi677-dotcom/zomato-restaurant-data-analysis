# 🍽️ Zomato Restaurant Data Analysis

Exploratory data analysis (EDA) of Zomato restaurant data using Python,
covering restaurant types, votes, ratings, pricing, and online ordering.

## 📌 Project Overview
This project analyzes 148 restaurants to understand which restaurant
types are most common, how customers rate them, how much couples
typically spend, and whether online ordering relates to better ratings.

## 📂 Dataset
- **File:** `data/zomato_data.csv`
- **Size:** 148 rows × 7 columns, no missing values

| Column | Description |
|---|---|
| `name` | Restaurant name |
| `online_order` | Online ordering available (Yes/No) |
| `book_table` | Table booking available (Yes/No) |
| `rate` | Rating out of 5 (converted from "4.1/5" to 4.1) |
| `votes` | Number of votes received |
| `approx_cost(for two people)` | Approximate cost for two people |
| `listed_in(type)` | Restaurant type (e.g., Buffet, Dining) |

## 🛠️ Tools & Libraries
Python 3 · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## 📁 Project Structure
```
zomato-restaurant-data-analysis/
├── data/
│   └── zomato_data.csv
├── notebooks/
│   └── zomato_data_analysis.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## 🔍 Analysis Steps
1. Import necessary libraries
2. Load the dataset
3. Convert the `rate` column to float
4. Check dataframe info
5. Countplot of restaurant types
6. Total votes per restaurant type
7. Ratings distribution (histogram)
8. Approximate cost distribution for couples
9. Online vs offline ratings (boxplot)
10. Heatmap of restaurant type vs online order

## 📊 Key Insights
- *(Add after reviewing your charts)*
- *(e.g. "Dining is the most common restaurant type")*
- *(e.g. "Most restaurants are rated between 3.5 and 4.0")*

## 🚀 How to Run
```bash
git clone https://github.com/<your-username>/zomato-restaurant-data-analysis.git
cd zomato-restaurant-data-analysis
pip install -r requirements.txt
jupyter notebook notebooks/zomato_data_analysis.ipynb
```

## 🔗 Source
Original Kaggle notebook by sakshidekate:
https://www.kaggle.com/code/sakshidekate/zomato-data-analysis-using-python

## 👤 Author
**Your Name** · [GitHub](https://github.com/your-username) · [LinkedIn](https://linkedin.com/in/your-profile)
