# 📊 EDA & Storytelling with Data — Global Superstore Sales
### SkillsHunger 2026 AI Internship Program — Task 01

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-orange?style=flat-square)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-red?style=flat-square)

---

## 🎯 Objective

Perform comprehensive Exploratory Data Analysis (EDA) on a real-world retail dataset and communicate findings through effective data visualizations and a business-focused Client Insight Card.

---

## 📊 Dataset

**Source:** [Global Superstore — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

| Detail | Value |
|---|---|
| Rows | 9,994 transactions |
| Columns | 21 features |
| Domain | Retail / Sales Analytics |
| Date Range | 2014 – 2017 |
| Target | Sales, Profit, Discount patterns |

---

## 📁 Project Structure

```
Task01-EDA-Superstore/
│
├── 📓 task01_eda_analysis.ipynb         # Main EDA notebook
├── 📄 README.md                         # This file
├── 🖼️  task01_client_insight_card.html  # Business insight card
└── 📦 requirements.txt                  # Dependencies
```

---

## 🧹 Data Cleaning Steps

- Removed duplicate rows
- Converted `Order Date` and `Ship Date` to datetime format
- Extracted time features: Year, Month, Ship Days
- Renamed columns for clarity (removed spaces, standardized naming)
- Verified and handled missing values
- Validated data types across all columns

---

## 📈 Visualizations (7 Charts — 6 Types)

| # | Chart Type | Title |
|---|---|---|
| 1 | **Bar Chart** | Sales & Profit by Product Category |
| 2 | **Line Graph** | Monthly Sales Trend by Year |
| 3 | **Histogram** | Profit & Sales Distribution |
| 4 | **Heatmap** | Sub-Category Sales by Region |
| 5 | **Pie Chart** | Sales Share by Region & Segment |
| 6 | **Boxplot** | Profit Distribution by Sub-Category |
| 7 | **Scatter Plot** | Discount Impact on Profit |

---

## 🔍 Key Findings

### 1. Q4 Seasonality (Nov–Dec Peak)
Sales consistently spike every November–December across all years. Q4 accounts for 35%+ of annual revenue — holiday season demand is the strongest revenue driver.

### 2. Discount = Profit Killer
Discounts above 20% consistently result in negative profit across all categories. The company has a serious over-discounting problem that is eroding margins.

### 3. Furniture is a Loss Centre
Tables and Bookcases have **negative median profit**. Tables alone generated over $17K in losses. High sales volume masks deep margin problems.

### 4. Technology is the Star Category
Technology has the highest sales ($836K) and best profit margins. This is where investment should be directed.

### 5. West Region Dominates
West region accounts for ~32% of total revenue. California alone leads state-level sales. Other regions can replicate West's approach.

---

## 💡 Actionable Recommendation

**"Profit First" Discount Policy:**
- Cap all discounts at a maximum of **20%**
- Eliminate discounts on Furniture sub-categories (Tables, Bookcases)
- Redirect recovered margin into Technology product expansion
- Prepare Q4 inventory 3 months in advance

---

## 📦 Requirements

```bash
pip install -r requirements.txt
```

```
pandas==2.0.3
numpy==1.24.3
matplotlib==3.7.2
seaborn==0.12.2
jupyter==1.0.0
```

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/Task01-EDA-Superstore.git
cd Task01-EDA-Superstore

# Install dependencies
pip install -r requirements.txt

# Download dataset from Kaggle
# Place 'Sample - Superstore.csv' in root folder

# Run notebook
jupyter notebook task01_eda_analysis.ipynb
```

---

## 👤 Author

**[Your Name]**  
SkillsHunger AI Internship 2026  
Task 01 — EDA & Storytelling with Data

---

## 📜 License

MIT License — For educational and internship submission purposes.
