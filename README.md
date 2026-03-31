
# 🛒 Blinkit Sales Data Analysis — Python Project

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Blinkit's grocery sales dataset using Python. The goal is to uncover trends and patterns across product types, outlet types, locations, and fat content to derive actionable business insights.

---

## 🗂️ Dataset Description

**File:** `blinkit_data.csv` — 8,523 rows of transactional sales data

| Column | Description |
|--------|-------------|
| `Item Fat Content` | Fat category of the item (Low Fat / Regular) |
| `Item Identifier` | Unique product ID |
| `Item Type` | Product category (Fruits & Vegetables, Snack Foods, Dairy, etc.) |
| `Outlet Establishment Year` | Year the outlet was established |
| `Outlet Identifier` | Unique outlet ID |
| `Outlet Location Type` | Tier 1 / Tier 2 / Tier 3 city |
| `Outlet Size` | Small / Medium / High |
| `Outlet Type` | Grocery Store / Supermarket Type 1/2/3 |
| `Item Visibility` | % shelf visibility of the product |
| `Item Weight` | Weight of the product |
| `Sales` | Sales value of the item |
| `Rating` | Customer rating |

---

## 🔍 Key Analysis Performed

- **Data Cleaning** — Handled missing values in `Item Weight` and standardized inconsistent values in `Item Fat Content` (e.g., `LF`, `low fat` → `Low Fat`)
- **Univariate Analysis** — Distribution of Sales, Ratings, and Item Types
- **Bivariate Analysis** — Sales vs Outlet Type, Sales vs Item Fat Content, Sales vs Location Tier
- **Outlet Performance** — Compared sales across different outlet sizes and establishment years
- **Item Category Insights** — Identified top-performing product categories by revenue

---

## 💡 Key Insights

- 🏪 **Supermarket Type 1** outlets generate the highest total sales
- 🌆 **Tier 3** cities contribute significantly to overall revenue
- 🥗 **Fruits & Vegetables** and **Snack Foods** are the top-selling item categories
- 🧴 **Low Fat** items are more popular than Regular items across most outlets
- 📅 Outlets established around **1998 and 2000** show strong long-term sales performance

---

## 🛠️ Tools & Libraries Used

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical operations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualizations |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📁 Project Structure

```
Blinkit-Python-project/
│
├── Blinkit py.ipynb       # Main analysis notebook
├── blinkit_data.csv       # Raw dataset
└── README.md              # Project documentation
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/vishvajitshelke/Blinkit-Python-project.git
   ```

2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Blinkit py.ipynb"
   ```

---

## 👤 Author

**Vishvajit Shelke** — Data Analyst | Python & Power BI Developer

---

*Dataset contains 8,523 records across multiple outlet types and product categories.*

