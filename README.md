# 📡 API Monitor Bot

A Python-based automation tool that monitors public API endpoints for specific keywords in real-time (e.g., "RFP", "GenAI", "Selenium").  
Designed to detect new government contract listings or research opportunities and send instant alerts.

---

## ✅ What It Does

- Connects to public APIs like:
  - [SBA.gov Contract Opportunities](https://www.sba.gov)
  - [GSA Open Opportunities](https://open.gsa.gov/api/get-opportunities-public-api/)
- Scans documents for keywords like:
  - "RFP", "RFI", "Sources Sought", "AI", "GenAI", "Selenium"
- Sends alerts via:
  - Email, Telegram, or webhook
  - Optional n8n or Zapier integration
- Supports scheduling for daily/hourly polling

---

## 🧠 Use Cases

- Government contract monitoring  
- AI opportunity tracking  
- Custom procurement alert system

---

## 🛠 Technologies

- Python 3  
- `httpx` 
- `n8n` or webhook/Telegram APIs  
- Keyword filtering logic  
- Optional: cron job or cloud run

---

## 📁 Output

- JSON alerts  
- Message logs  
- Configurable keyword + agency filters

---

## 🔐 Access

🔒 Source code is private.  
This page showcases intelligent alert automation from public data streams.

---

## 🧑‍💻 Author

**TrkElnIt** – Smart alerting tools for open data and procurement signals  

