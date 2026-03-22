# 📊 Week 6 – Exploratory Data Analysis (EDA)

🔗 My Colab Work:
https://colab.research.google.com/drive/1t6HBHcImsG7lI_3L7lvJEcCjoLWGmNtp

---

## 🔹 1. Dataset Overview

- Loaded dataset using Pandas
- Checked:
  - Shape
  - Data types
  - Missing values

### Output:
- Structured dataset with multiple numerical and categorical fields  

---

## 🔹 2. Data Inspection

### Methods Used:
- `head()`
- `info()`
- `describe()`

### Findings:
- Numerical columns showed variation in values
- Some columns had missing data  

---

## 🔹 3. Distribution Analysis

### What I Did:
- Checked value counts
- Analyzed merchant frequency

### Output:
- Few merchants dominate transactions  
- Long-tail distribution observed  

---

## 🔹 4. Filtering Analysis

### What I Did:
- Extracted transactions:
  - amount > 500
  - amount > 1000

### Output:
- Identified high-value transactions  
- Found patterns in spending behavior  

---

## 🔹 5. Group Analysis

### What I Did:
- Grouped by merchant
- Calculated:
  - Sum
  - Mean

### Output:
- Identified top-performing merchants  
- Observed uneven distribution  

---

## 🔹 6. Correlation EDA

### What I Did:
- Built correlation matrix

### Output:
- Strong relation: Cases vs Deaths  
- Weak relation: Vaccination vs Deaths :contentReference[oaicite:8]{index=8}  

---

## 🔹 7. Outlier Detection

### What I Did:
- Used sorting and IQR method

### Output:
- Found extreme values  
- Verified outliers visually  

---

## 🔹 8. Visualization (Conceptual)

- Scatter plots used for:
  - Cases vs Deaths  
- Trendlines added for analysis  

### Output:
- Visual confirmation of relationships  

---

## 📌 Conclusion

EDA helped in:
- Understanding dataset structure  
- Identifying patterns and anomalies  
- Preparing data for modeling  