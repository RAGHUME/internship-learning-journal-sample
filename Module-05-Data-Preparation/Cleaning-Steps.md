# 🧹 Week 5 – Cleaning Steps

🔗 My Colab Work:
https://colab.research.google.com/drive/1oLeCL3p2b8yw66797CKNXLKhmqy5_zZ8

---

## 🔹 1. Cleaning Data in Excel

### ✔ Steps Performed:
- Used **Find & Replace (Ctrl + H)** to remove unwanted values  
- Converted data types (General → Number / Date)  
- Applied `=TRIM()` to remove extra spaces  
- Deleted blank rows using **Go To Special → Blanks**  
- Removed duplicate entries  

### 📊 Output Observed:
- Cleaned dataset without extra spaces  
- Consistent formatting across columns  
- No duplicate or empty records  

---

## 🔹 2. Text to Columns

### ✔ Steps Performed:
- Split combined data using delimiters (`(`, `-`, `,`, `)`)  

### 📊 Output Observed:
- Converted single messy column into:
  - Name  
  - Party  
  - State  
  - Vote  

### Learning:
Structured data is easier to analyze and process.

---

## 🔹 3. Data Cleaning using Unix Shell

### ✔ Steps Performed:
- Downloaded dataset using `curl`  
- Decompressed using `gzip`  
- Viewed data using `head`, `tail`  
- Extracted columns using `cut`  
- Counted duplicates using `uniq`  
- Filtered logs using `grep`  

### 📊 Output Observed:
- Identified most active IPs  
- Found bot activity in logs  
- Extracted specific fields like IP addresses  

---

## 🔹 4. Cleaning Logs using sed

### ✔ Steps Performed:
- Converted log format to CSV using `sed`

### 📊 Output Observed:
- Clean CSV file ready for Excel analysis  

---

## 🔹 5. Data Cleaning in DuckDB

### ✔ Steps Performed:
- Used `COALESCE()` to handle NULL values  
- Used `TRIM()` and `LOWER()` for string cleaning  
- Applied `REGEXP_REPLACE()` for formatting  

### 📊 Output Observed:
- Missing values replaced with default values  
- Clean and standardized text fields  

---

## 📌 Conclusion

- Cleaned data using Excel, Shell, and SQL  
- Removed duplicates, blanks, and inconsistencies  
- Prepared dataset for further analysis  