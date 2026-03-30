# 📘 Week – Learnings
🔗 My Colab Work:
https://colab.research.google.com/drive/1ZWnsfklrAHGOclVcIY3Tj4b20e95fHhq

---

---

## 🔹 1. Data Preparation using Pivot Tables

### What I Did:
- Structured time-series data
- Organized:
  - Rows → Dates
  - Columns → Securities

### Learning:
- Clean structure is required before analysis  
- Pivot tables simplify large datasets  

---

## 🔹 2. Trend Visualization (Sparklines)

### What I Did:
- Created sparklines for each security

### Learning:
- Quick way to identify trends  
- Helps compare multiple time series visually  

---

## 🔹 3. Forecasting using GROWTH

### What I Did:
- Converted dates to numeric values
- Predicted future values using:

```excel
=GROWTH(y_values, x_values, new_x)
