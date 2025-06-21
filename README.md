# 🧱 LEGO Power BI Dashboard

Welcome to my LEGO dataset analysis project! This repository contains an interactive Power BI dashboard that explores various LEGO sets, their prices, age ranges, piece counts, and theme categories.

---

## 📌 **Project Overview**

- **Domain:** Retail / Toy Industry
- **Tools Used:** Power BI, DAX
- **Dataset:** LEGO sets with attributes such as price, theme, category, age range, and piece count.
- **Objective:**
  - Analyze trends in LEGO sets by category, age group, and theme.
  - Provide insights into average pricing and piece counts.
  - Enable users to interactively filter and explore sets.

---

## ⚡ **Key KPIs**

- **Average Price:** `$45`
- **Total Sets:** `4385`
- **Average Pieces per Set:** `411`

---

## 📂 **Repository Structure**

| Folder | Description |
|--------|--------------|
| `Data/` | Contains source dataset(s) if allowed, or a link to the data source. |
| `Reports/` | `.pbix` file and exported `.pdf` version of the dashboard. |
| `Images/` | Screenshots used in this README. |
| `Scripts/` | DAX measures, calculated columns, or SQL if preprocessing is done. |
| `Documentation/` | Project summary, insights, or additional notes. |

---

## 📊 **Dashboard Pages**

### **1️⃣ Page 1 — LEGO Sets Overview**
- **Features:**
  - Filter sets by theme group, age range, and theme.
  - View key metrics: Avg. Price, Total Sets, Avg. Pieces.
  - Interactive table with set name, ID, theme, age range, avg. price, and piece count.
  - Single set image preview.

![Page 1]([Images/page1.png](https://github.com/PaulSourav10/Lego_set_analysis/blob/main/Dash%20board%20screenshots/Lego_set_analysis_page%201.jpg))

---

### **2️⃣ Page 2 — Hierarchy Analysis**
- **Features:**
  - Hierarchical tree breakdown: Category → Theme Group → Theme → Set Name.
  - Visualizes how sets are distributed across different themes and categories.
  - Consistent KPI cards for easy context.

![Page 2]([Images/page2.png](https://github.com/PaulSourav10/Lego_set_analysis/blob/main/Dash%20board%20screenshots/Lego_set_analysis_page%202.jpg))

---

## 🧩 **Key DAX Measures**

Custom measures built for this dashboard:
- `Avg_price`
- `Avg_pieces`
- `Avg_age`
- `selected sets`, `selected price`, `selected pieces`, etc.
- Parameter for maximum price filtering.

These enable dynamic insights as users interact with slicers and the hierarchy visual.

---

## ✅ **View the Live Dashboard**

👉 [**Click here to view the interactive Power BI Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiM2Y1Y2RjZTItYjI3MC00NjM3LWExNzQtZmEzYTMyOGJhMTY3IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## ⚙️ **How to Use**

1. **Online:** Use the link above to view and interact with the published dashboard.
2. **Locally:** Download the `.pbix` file from `Reports/` and open it in **Power BI Desktop**.
3. Explore filters, hierarchy drilldowns, and key metrics.

---

## 📃 **License**

This project is for **educational purposes only** — all LEGO trademarks belong to the LEGO Group.

---

## 🔗 **Connect with Me**

- [LinkedIn]((https://www.linkedin.com/in/souravpaulofficial/))

- [Email]
- souravpaulofficial101@gmail.com

---

> **Note:** This is an educational project and does not imply any affiliation with the LEGO Group.
