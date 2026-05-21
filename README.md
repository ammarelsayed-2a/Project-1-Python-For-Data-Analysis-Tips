# 🔍 Exploratory Data Analysis — Tips Dataset

A structured EDA project on the built-in Seaborn `tips` dataset, completed as part of the **Python for Data Analysis** course.

## 📌 Objective
Explore and understand the dataset through statistical summaries and visualizations — covering data structure, distributions, relationships, and key insights.

## 📂 Dataset
- **Source:** Seaborn built-in datasets (`sns.load_dataset('tips')`)
- **Records:** 244 restaurant bills
- **Features:** total_bill, tip, sex, smoker, day, time, size

## 🛠️ Tools & Libraries
| Library | Purpose |
|---|---|
| Pandas | Data loading, exploration, and statistics |
| NumPy | Numerical operations |
| Matplotlib | Base plotting |
| Seaborn | Statistical visualizations |

## 📊 Analysis Structure
1. Imports & Setup
2. Load Dataset
3. First Look (head / tail)
4. Data Structure & Info
5. Missing Values Check
6. Descriptive Statistics
7. Categorical Exploration
8. Univariate Analysis — Numerical
9. Univariate Analysis — Categorical
10. Bivariate Analysis — Numerical vs Numerical
11. Bivariate Analysis — Numerical vs Categorical
12. Bivariate Analysis — Categorical vs Categorical
13. Multivariate Analysis
14. Correlation Heatmap
15. Pairplot
16. Key Insights

## 💡 Key Insights
- Higher bills are positively correlated with higher tips
- Over 65% of visits occur on weekends (Sat & Sun)
- Party size is a strong driver of total bill amount
- Total bill distribution is right-skewed — most bills fall between $10–$25
- Tip percentage slightly decreases as the bill grows larger

## 🚀 How to Run
```bash
git clone https://github.com/ammarelsayed-2a/Project-1-Python-For-Data-Analysis-Tips-.git
cd Project-1-Python-For-Data-Analysis-Tips-
jupyter notebook "Project 1 Tips.ipynb"
```

## 👤 Author
**Ammar Elsayed** — Python for Data Analysis | 2026
[LinkedIn](https://www.linkedin.com/in/ammar-elsayed-ibrahim)
