# -UPI-Transaction-Data-Analysis-Indian-Banking-Sector-Performance

# 📊 UPI Transaction Data Analysis in Indian Banking Sector

![UPI Logo](data:image/png;base64,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)

## 🔍 What is UPI?

Unified Payments Interface (UPI) is a real-time payment system developed by the **National Payments Corporation of India (NPCI)** that facilitates inter-bank transactions via mobile platforms. It allows users to send or receive money instantly using a UPI ID, without needing bank account details.

- Launched in **2016**
- Processes over **10+ billion transactions per month** *(as of 2024)*
- Powers apps like **Google Pay, PhonePe, Paytm, BHIM, Amazon Pay**, etc.

---

## 🚀 Why I Selected This Project

The UPI ecosystem is one of the fastest-growing digital payment systems globally, but there's **no single source of truth** for performance metrics across all banks. Most data is scattered, semi-structured, and hidden in HTML tables or PDFs.

This project was an opportunity to:
- Solve a **real-world data collection** problem using scraping.
- **Analyze and compare** bank performance in terms of volume, success rates, and market share.
- Build a **clean dashboard-style application** using Streamlit and SQL.

---

## 📈 Growth of UPI

- In 2017, UPI handled around **100 million transactions per month**.
- By 2024, it crossed **10 billion monthly transactions**.
- Over **300 banks** are part of the UPI ecosystem.
- Rapid growth driven by:
  - Smartphone penetration
  - Government push for digital payments
  - Rise of fintech apps
  - Seamless integration across platforms

---

## 🧰 Tools & Technologies Used

| Tool / Library      | Purpose                          |
|---------------------|----------------------------------|
| `Python`            | Core programming language        |
| `Streamlit`         | Web app/dashboard creation       |
| `BeautifulSoup`     | Web scraping (HTML parsing)      |
| `Selenium`          | Automating data extraction       |
| `Pandas & NumPy`    | Data cleaning and manipulation   |
| `SQL (SQLite)`      | Data storage and querying        |
| `Matplotlib/Plotly` | Visualizations (if used)         |

---

## ⚙️ Project Features

- 📊 Interactive dashboard to explore UPI data
- 🕵️‍♂️ Scrapes real UPI data from NPCI or bank sites
- 🔎 Bank-wise comparison on volume, success rate, and failure rate
- 📉 Trends in market share over time
- 💾 Data stored and queried using SQL

---

## 🧠 Key Takeaways

- **Private Players** tend to dominate the upi apps market. Phonepe leads the way.
- Some banks show **high success rates**, while others struggle with failure spikes.
- Public sector banks are **improving gradually** and closing the gap (especially SBI).
- **No single API or open dataset exists**, so scraping + cleaning are essential skills here.
- SQL queries helped unlock hidden patterns in bank-wise performance.
