# 🛍️ Selling Purses Online Using Web Scraping & API

## 📌 Overview
This project focuses on leveraging **web scraping** and **Amazon API** to optimize purse sales by analyzing demand, pricing trends, and customer preferences.

## 🚀 Features
- Extracts **real-time product data** from Myntra, Amazon, and Flipkart
- Analyzes **best-selling purses, price trends, and customer reviews**
- Identifies **demand fluctuations and seasonal trends**
- **Optimizes product selection & pricing** using data insights

## 🛠️ Installation
Ensure you have **Python 3.x** installed, then run:

```bash
pip install -r requirements.txt
```

### **Required Libraries**
```bash
pip install selenium beautifulsoup4 pandas webdriver-manager requests
```

## 🔧 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/purse-scraper.git
   cd purse-scraper
   ```
2. Run the script for Myntra scraping:
   ```bash
   python myntra_scraper.py
   ```
3. Use the Amazon API to fetch product details:
   ```bash
   python amazon_api.py
   ```
4. Scraped data is saved in `purses_data.csv`

## 📊 Extracted Data Fields
- **Brand**
- **Product Name**
- **Discounted Price**
- **Original Price**
- **Rating**
- **Reviews Count**
- **Material Info**
- **Availability** (In Stock/Out of Stock)
- **Seller Info**
- **Product URL**

## 🔄 Implementation Plan
1. **Identify Best-Selling Purses** using web scraping
2. **Analyze Pricing Trends & Demand Patterns**
3. **Find Suppliers** for sourcing products at the best price
4. **Set Competitive Pricing** to maximize profit
5. **Choose the Best Platform** for listing the products

## 📈 Business Potential
- **Data-driven pricing increases profitability**
- **Identifying trends helps in selecting the right products**
- **Competitive intelligence helps outperform competitors**
- **Automation reduces research time and improves efficiency**

## 🏗️ Project Structure
```
📂 purse-scraper
 ├── 📝 README.md
 ├── 📜 requirements.txt
 ├── 🖥️ myntra_scraper.py
 ├── 🖥️ amazon_api.py
 ├── 📊 purses_data.csv (output)
```

## ⚠️ Notes
- **Myntra and Amazon's website structure may change**, requiring updates to the script.
- Using a headless browser (`--headless`) allows background execution.
- **Avoid excessive requests** to prevent IP blocking.

## 📌 To-Do
- [ ] Add Flipkart scraping
- [ ] Store data in a database (SQLite, MongoDB, etc.)
- [ ] Implement proxy rotation to prevent blocks

## 📄 License
This project is licensed under the **MIT License**.

---

🔗 **Connect with Me:** [LinkedIn](https://linkedin.com/in/your-profile) | [GitHub](https://github.com/your-username)


