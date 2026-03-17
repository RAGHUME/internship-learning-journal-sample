# 📘 Week 4 – Learnings

🔗 My Colab Work:
https://colab.research.google.com/drive/1JcizpLhksd71gDIwUVuYoW9J2ZCTBnJ7

---

## 🔹 1. Backend API Extraction

- Used browser DevTools → Network tab
- Identified hidden API calls used by websites

### Output Observed:
- Received clean JSON responses instead of HTML
- Extracted data directly using `requests.get()`

### Learning:
Using APIs is faster and more reliable than scraping HTML.

---

## 🔹 2. Geocoding with Geopy

- Used Nominatim for forward and reverse geocoding

### Output Observed:
- Address → Latitude & Longitude  
- Example: "IIT Madras" → (12.99, 80.23)

### Additional Observation:
- Invalid locations returned `None`
- Used RateLimiter to avoid blocking

### Learning:
Geocoding helps convert location data into usable coordinates.

---

## 🔹 3. Wikipedia Data Extraction

- Used `wikipedia` Python package

### Output Observed:
- Search → list of article titles  
- Summary → short description  
- Page → URL, images, references  

### Learning:
Wikipedia API provides structured data easily without scraping.

---

## 🔹 4. JavaScript Scraping (Browser)

- Used browser console (`$$`, `querySelector`)

### Output Observed:
- Extracted IMDb Top 250 movie data
- Fields:
  - Title  
  - Year  
  - Rating  
  - Duration  

### Learning:
Quick scraping can be done without Python using browser tools.

---

## 🔹 5. Requests vs Playwright

- Tried scraping using `requests`
- Observed missing data (empty HTML)

### Output Observed:
- `requests` → no table data  
- `playwright` → full rendered HTML  

### Learning:
Use Playwright for JavaScript-based websites.

---

## 🔹 6. Playwright Scraping

- Used Playwright to render dynamic pages

### Output Observed:
- Extracted NASDAQ table into DataFrame  
- Successfully loaded dynamic content  

### Learning:
Playwright executes JavaScript and gives complete page data.

---

## 🔹 7. PDF Scraping

- Used BeautifulSoup to download PDFs
- Used Tabula to extract tables

### Output Observed:
- Extracted tables into CSV format  
- Converted PDF data into structured format  

### Learning:
PDF data can be automated and converted into datasets.

---

## 🔹 8. MarkItDown Conversion

- Converted PDF → Markdown

### Output Observed:
- Clean text extracted from documents  
- Easy to use for further processing  

### Learning:
Markdown format is useful for LLM and text analysis.

---

## 🔹 9. LLM-Based Scraping

- Used LLM to extract structured data from text

### Output Observed:
- Converted messy webpage content → JSON  
- Extracted fields like title, price, etc.  

### Learning:
LLMs reduce manual parsing effort.

---

## 🔹 10. Scheduled Scraping (GitHub Actions)

- Created automated scraping workflow

### Output Observed:
- Data saved daily as JSON files  
- Timestamp added automatically  

### Learning:
Automation helps build continuous datasets.

---

## 🔹 11. Overall Learning

- Learned multiple data sourcing techniques  
- Compared APIs, scraping, and LLM extraction  
- Understood real-world data pipeline  

---

## 📌 Conclusion

- Successfully extracted data from APIs, websites, PDFs, and LLMs  
- Built practical understanding of data sourcing  
- Learned automation using GitHub Actions  