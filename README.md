# 🛍️ Diwali Sales Analysis — Python EDA Project

An end-to-end Exploratory Data Analysis (EDA) project on Indian e-commerce Diwali sales data, built using Python, Pandas, Matplotlib, and Seaborn. The goal was to identify the highest-value customer segments and product categories to support data-driven marketing decisions.

---

## 📊 Dataset Overview

| Attribute | Detail |
|-----------|--------|
| Rows | 11,251 |
| Columns | 15 |
| Total Revenue | ₹10.6 Crore |
| States Covered | 16 |
| Product Categories | 18 |

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data cleaning & manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |
| Jupyter Notebook | Analysis environment |

---

## 🔍 Analysis Performed

- **Data Cleaning** — Dropped irrelevant columns, handled null values (12 rows), fixed data types
- **Exploratory Data Analysis** — Analyzed 6 dimensions: Gender, Age Group, State, Marital Status, Occupation, Product Category
- **Quantified Insights** — Calculated % revenue contribution per segment, average order values, and top-N breakdowns
- **Correlation Analysis** — Examined relationships between Age, Orders, and Amount
- **Business Recommendations** — Translated findings into 4 actionable marketing decisions

---

## 📈 Key Findings

| Dimension | Finding |
|-----------|---------|
| Gender | Female buyers = **70% of total revenue (₹7.4 Crore)** |
| Age Group | 26–35 = highest revenue volume; 51–55 = highest avg order value (₹9,954) |
| Geography | Top 3 states (UP, Maharashtra, Karnataka) = **44.5% of total revenue** |
| Marital Status | Married women alone = **28.8% of total revenue (₹3.06 Crore)** |
| Occupation | IT, Healthcare & Aviation = top 3 sectors by revenue |
| Product Mix | Food + Clothing + Electronics = **62.2% of total revenue** |

---

## 👤 Target Customer Profile

> **Married women, aged 26–35, from Uttar Pradesh / Maharashtra / Karnataka, working in IT, Healthcare, or Aviation** — this segment represents the core Diwali buyer and should be the primary target for campaign spend and inventory planning.

---

## 💡 Business Recommendations

1. **Concentrate ad spend** on married women aged 26–35 in UP, Maharashtra, and Karnataka for maximum Diwali campaign ROI.
2. **Stock up on Food, Clothing & Apparel, and Electronics** before peak season — a stockout in these 3 categories risks losing 62% of potential revenue.
3. **Design high-value product bundles** for the 51–55 age segment — they have the highest spend per order despite lower volume.
4. **Prioritize digital channels** — IT and Healthcare professionals (top buyer occupations) are the most digitally active segments.

---

## 📁 Project Structure

```
📦 Diwali-Sales-Analysis
 ┣ 📓 Diwali_Sales_Analysis.ipynb   # Main notebook with all analysis & charts
 ┣ 📄 Diwali Sales Data.csv         # Raw dataset
 ┗ 📄 README.md                     # Project overview (this file)
```

---

## ▶️ How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/sadaf355/Diwali-Sales-Analysis.git
   cd Diwali-Sales-Analysis
   ```

2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Launch Jupyter Notebook
   ```bash
   jupyter notebook
   ```

4. Open `Diwali_Sales_Analysis.ipynb` and run **Kernel → Restart & Run All**

---

## 🧠 Skills Demonstrated

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Exploratory Data Analysis (EDA)` `Data Cleaning` `Data Visualization` `Customer Segmentation` `Business Insights` `Correlation Analysis` `KPI Reporting`

---

*Project by [Shaikh Sadaf Noor](https://www.linkedin.com/in/sadaf-shaikh-004375281/) · [GitHub](https://github.com/sadaf355)*
