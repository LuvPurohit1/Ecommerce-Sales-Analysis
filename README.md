# 🛒 E-Commerce Sales Analysis

> An end-to-end Data Analytics project analyzing e-commerce sales performance, profitability, regional trends, and discount impact using **Python** and **Power BI**.

---

## 📊 Key Results

| Metric | Result |
|---|---|
| 💰 Total Sales | **$2,296,195.59** |
| 📈 Total Profit | **$286,241.42** |
| 📊 Overall Profit Margin | **1,198.37%** |
| 🏆 Most Profitable Sub-Category | Copiers — **$55,617.82 profit** |
| 📉 Highest Loss Sub-Category | Tables — **$17,725.48 loss** |
| 🔍 Avg Profit per Order | **$28.69** |

---

## 🎯 Project Objective

Analyze e-commerce sales data to uncover:
- Revenue and profit drivers across categories
- Regional sales and profitability trends
- Impact of discounts on profit margins
- Loss-making products and segments
- Data-driven recommendations for business decisions

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## 📂 Dataset

**Source:** [Sample Superstore Dataset — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
**File:** `Cleaned_SampleSuperstore.csv`
**Features:** Order ID, Sales, Profit, Discount, Category, Sub-Category, Region, Segment

---

## 📁 Project Structure

```
ecommerce-sales-analysis/
│
├── Dashboard/
│   ├── E-Commerce Sales Analysis 1.png
│   ├── E-Commerce Sales Analysis 2.png
│   └── E-Commerce Sales Analysis 3.png
├── Data/
│   ├── Cleaned_SampleSuperstore.csv
│   └── SampleSuperstore.csv
├── Notebook/
│   └── sales_analysis.ipynb
├── requirements.txt
└── README.md
```

---

## 🔍 Exploratory Data Analysis (EDA)

- **Category Performance** — Technology is the most profitable category
- **Sub-Category Analysis** — Copiers lead profit at $55,617; Tables cause highest loss at -$17,725
- **Discount Impact** — Higher discounts directly lead to losses; lower discounts maintain profitability
- **Regional Analysis** — West region is most profitable; other regions show higher sales but lower efficiency
- **Profit Margin** — Overall profit margin of 1,198% shows strong business performance at scale

---

## 💡 Key Business Insights

- 🖨️ **Copiers** are the star sub-category with **$55,617.82 profit** — priority product for business
- 🪑 **Tables** are the biggest loss-maker at **-$17,725.48** — discount strategy needs revision
- 📉 **Excessive discounting kills profit** — orders with high discounts consistently show negative margins
- 🌍 **West region** outperforms others in profitability — a model for other regions to follow
- 💰 With **$2.29M total sales** and **$286K profit**, overall business health is strong but uneven across segments

---

## 📊 Power BI Dashboard

Interactive dashboard with category, regional, and profitability analysis.

### Page 1 — Sales Overview
![Dashboard Page 1](Dashboard/E-Commerce%20Sales%20Analysis%201.png)

### Page 2 — Category & Profit Analysis
![Dashboard Page 2](Dashboard/E-Commerce%20Sales%20Analysis%202.png)

### Page 3 — Regional & Discount Analysis
![Dashboard Page 3](Dashboard/E-Commerce%20Sales%20Analysis%203.png)

---

## ⚙️ How to Run

```bash
# 1. Clone the repo
git clone https://github.com/LuvPurohit1/ecommerce-sales-analysis.git

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the notebook
jupyter notebook sales_analysis.ipynb
```

---

## 🚀 Future Improvements

- [ ] Build a sales forecasting model (ARIMA / Prophet)
- [ ] Add customer segmentation using KMeans clustering
- [ ] Deploy an interactive Streamlit dashboard
- [ ] Analyze seasonal trends and peak sales periods
- [ ] Add RFM (Recency, Frequency, Monetary) analysis

---

## 👤 Author

**Luv Purohit**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luv-purohit-40693634a)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/LuvPurohit1)
