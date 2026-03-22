# 📘 Week 6 – Learnings

🔗 My Colab Work:
https://colab.research.google.com/drive/1t6HBHcImsG7lI_3L7lvJEcCjoLWGmNtp

---

## 🔹 1. Data Analysis using Pandas

### What I Did:
- Loaded dataset using `read_parquet()`
- Explored data using:
  - `head()`
  - `info()`
  - `describe()`
- Checked unique values and counts

### Output Observed:
- Understood dataset structure (columns, types, missing values)
- Identified key columns like merchant, amount
- Found distribution of transactions across merchants :contentReference[oaicite:0]{index=0}  

---

## 🔹 2. Data Filtering & Grouping

### What I Did:
- Filtered transactions (`amount > 1000`)
- Grouped data using `groupby()`
- Calculated:
  - Total spending
  - Average spending per merchant

### Output Observed:
- Identified top merchants by revenue
- Found high-value transactions easily
- Observed spending patterns per merchant  

---

## 🔹 3. SQL + Pandas Integration

### What I Did:
- Connected to database using SQLAlchemy
- Ran SQL queries inside Python
- Analyzed results using Pandas

### Output Observed:
- Verified database connectivity
- Extracted aggregated data (post counts, users)
- Learned hybrid workflow (SQL + Python)  

---

## 🔹 4. Pareto Analysis (80/20 Rule)

### What I Did:
- Calculated top 20% users contribution

### Output Observed:
- Top 20% users generated ~76% of posts  
- Validated Pareto principle in real dataset :contentReference[oaicite:1]{index=1}  

---

## 🔹 5. Correlation Analysis (Excel)

### What I Did:
- Created correlation matrix
- Compared:
  - Cases vs Deaths
  - Vaccinations vs Deaths

### Output Observed:
- Strong correlation:
  - Cases vs Deaths → **0.84**
- Weak correlation:
  - Vaccinations vs Deaths → **0.23** :contentReference[oaicite:2]{index=2}  

---

## 🔹 6. Regression Analysis

### What I Did:
- Built regression model
- Used variables:
  - Cases, Tests, Vaccinations, Stringency

### Output Observed:
- Adjusted R² = **0.816** (strong model)
- Significant variables:
  - Cases, Tests, Vaccinations
- Non-significant:
  - Stringency index :contentReference[oaicite:3]{index=3}  

---

## 🔹 7. Forecasting

### What I Did:
- Used:
  - `FORECAST`
  - `TREND`
  - `FORECAST.ETS`

### Output Observed:
- Linear models worked for simple data
- ETS worked better for time-series patterns :contentReference[oaicite:4]{index=4}  

---

## 🔹 8. Outlier Detection

### What I Did:
- Used IQR method
- Identified extreme values

### Output Observed:
- Detected abnormal values (e.g., 200 in dataset)
- Learned impact of outliers on analysis :contentReference[oaicite:5]{index=5}  

---

## 🔹 9. DuckDB vs Pandas

### What I Did:
- Ran same queries in Pandas & DuckDB

### Output Observed:
- DuckDB was **20–25x faster**
- Better for large datasets :contentReference[oaicite:6]{index=6}  

---

## 🔹 10. Geospatial Analysis

### What I Did:
- Used geopy for distance calculation
- Created maps using folium

### Output Observed:
- Calculated real-world distances
- Visualized locations on map :contentReference[oaicite:7]{index=7}  

---

## 📌 Conclusion

- Learned complete **data analysis workflow**
- Combined tools:
  - Pandas + SQL + Excel + DuckDB
- Understood:
  - Correlation
  - Regression
  - Forecasting
  - Outliers