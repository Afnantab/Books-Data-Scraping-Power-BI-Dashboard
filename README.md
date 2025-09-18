

# 📚 Books Data Scraping & Power BI Dashboard  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)  
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Web%20Scraping-brightgreen.svg)  
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)  
![Excel](https://img.shields.io/badge/Excel-Data%20Storage-success.svg)  

## 📌 Overview  
This project demonstrates an **end-to-end data analysis pipeline** – from **web scraping books data using BeautifulSoup**, storing it into **Excel**, and finally creating an **interactive Power BI dashboard** to visualize insights.  

---

## 🔹 Project Workflow  
1. **Web Scraping**  
   - Extracted book details (title, price, rating, category, availability).  
   - Cleaned and structured data using **Pandas**.  

2. **Data Storage**  
   - Saved the processed dataset into an **Excel file**.  

3. **Power BI Dashboard**  
   - Imported the Excel dataset into Power BI.  
   - Designed an interactive dashboard for analysis.  

---

## 📊 Key Metrics in Dashboard  
- **Total Price:** $35.07K  
- **Price Range:** $10 – $59.99  
- **Total Availability:** 8,585 books  
- **Total Ratings:** 2,923  
- **Average Rating:** 2.92  

### 📈 Visualizations  
- Total Price by Category  
- Availability by Category  
- Ratings by Book Title  
- Category-wise Distribution of Books  

---

## 🛠️ Tech Stack  
- **Python**: BeautifulSoup, Pandas, OpenPyXL  
- **Excel**: Data export & storage  
- **Power BI**: Dashboard & insights visualization  

---

## 🚀 How to Run  

### 1️⃣ Scrape Data  
```bash
git clone https://github.com/yourusername/books-data-dashboard.git
cd books-data-dashboard
jupyter notebook "Books Scrap saved Excel.ipynb"
