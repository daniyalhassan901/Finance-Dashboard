# 📊 FinSight – Finance Analysis Dashboard

**Real-time insights into transactions, customers and risk.**

FinSight is an interactive finance analytics dashboard that helps you understand how money moves through a banking/payments business: how much is transacted, how much is earned in fees and tax, which customers and regions generate the most revenue, and how many transactions fail.

![Dashboard Preview](images/dashboard.png)

> 💡 Save your dashboard screenshot as `images/dashboard.png` in your repository so the preview above shows up.

---

## 📌 Table of Contents

1. [Project Overview](#-project-overview)
2. [Objectives](#-objectives)
3. [Key Metrics (KPIs)](#-key-metrics-kpis)
4. [Dashboard Visuals Explained](#-dashboard-visuals-explained)
5. [Filters & Interactivity](#-filters--interactivity)
6. [Key Insights](#-key-insights)
7. [Tools & Technologies](#-tools--technologies)
8. [Repository Structure](#-repository-structure)
9. [How to Use](#-how-to-use)
10. [Author](#-author)

---

## 🔎 Project Overview

This project analyses financial transaction data for the year **2026** (data shown covers **January to April**). The dashboard has two pages:

| Page | Purpose |
|------|---------|
| **Dashboard** | High-level summary of amounts, fees, tax, customers, regions and transaction health |
| **Transactions** | Detailed transaction-level view for deeper analysis |

All amounts are in **Indian Rupees (Rs)**.

---

## 🎯 Objectives

- Track overall transaction volume and value
- Measure revenue earned from **fees** and **tax**
- Compare performance against the **previous year**
- Identify the best-performing **customer segments**, **states** and **transaction types**
- Monitor **risk** through success, failed and pending transaction rates
- Understand **gender-wise** contribution to fees

---

## 📈 Key Metrics (KPIs)

| KPI | Value | vs Previous Year |
|-----|-------|------------------|
| **Total Amount** | Rs 45.32M | ▼ 1.18% |
| **Total Transactions** | 4.99K | ▲ 0.40% |
| **Avg Transaction Value** | Rs 9.08K | ▼ 1.57% |
| **Total Fees** | Rs 75.44K | ▲ 7.17% |
| **Total Tax** | Rs 13.57K | ▲ 7.14% |

**What this means:** Total transaction value and average ticket size dipped slightly, but fee and tax income grew by over 7%, showing revenue is growing faster than transaction value.

---

## 🧩 Dashboard Visuals Explained

### 1. Total Fees by Month
An area chart showing how fee income changes from January to April. Fees rise steadily and **peak in March**, then drop in April.

### 2. Total Fees by Transaction Status
A donut chart showing the health of transactions:

| Status | Fees | Share |
|--------|------|-------|
| ✅ Success | Rs 64.3K | 85.2% |
| ❌ Failed | Rs 8.2K | 10.9% |
| ⏳ Pending | Rs 3.0K | 3.9% |

### 3. Total Fees by Customer Segments
A bar chart comparing segments: **Retail** (Rs 39K) leads by a wide margin, followed by Premium (Rs 15K), SME (Rs 12K), Corporate (Rs 6K) and Wealth (Rs 4K).

### 4. Total Fees by State
A ranked bar chart of the top states: **Maharashtra** (Rs 11.7K), Gujarat (Rs 9.5K), Uttar Pradesh (Rs 9.4K), Karnataka (Rs 7.4K), Tamil Nadu (Rs 7.2K), Madhya Pradesh (Rs 6.1K) and Haryana (Rs 4.0K).

### 5. Transaction Type Analysis
A heat-mapped table showing **Amount, Number of Transactions, Fees and Tax** for each transaction type:
Fee Charge, Refund, Interest Credit, Bill Payment, Withdrawal, Card Payment, Investment, Deposit and Transfer.
**Transfer** is the largest type (Rs 12.28M, 0.9K transactions, Rs 21.3K fees).

### 6. Total Fees by Gender
A donut chart splitting fees between **Male (Rs 35.21K)** and **Female (Rs 40.23K)** customers.

---

## 🎛️ Filters & Interactivity

The left-hand panel lets you slice the whole dashboard:

- **Year** – choose the reporting year (currently 2026)
- **Dynamic Metric** – switch visuals between measures such as *Total Fees*
- **Occupations** – filter by customer occupation
- **Category** – filter by transaction category
- **Navigation buttons** – move between *Dashboard* and *Transactions* pages

---

## 💡 Key Insights

1. **Fee income is growing** (+7.17%) even though total transaction value is slightly down.
2. **Retail customers** generate the most fees, roughly 2.5x the next segment.
3. **Maharashtra, Gujarat and Uttar Pradesh** are the top three states by fees.
4. **Transfers** account for the biggest share of amount and fees among transaction types.
5. About **11% of transactions fail**, which is a clear opportunity to reduce revenue loss and improve customer experience.
6. **Female customers** contribute more fees than male customers.
7. Fees **peak in March**, which may point to seasonal activity (e.g., financial year-end).

---

## 🛠️ Tools & Technologies

- **Power BI** – dashboard design and visualisation
- **DAX** – measures such as year-over-year change and dynamic metrics
- **Power Query** – data cleaning and transformation
- *(Add any others you used, e.g., Excel, SQL, Python)*

---

## 📁 Repository Structure

```
FinSight-Finance-Dashboard/
│
├── README.md
├── FinSight.pbix          # Power BI report file
├── data/                  # Dataset (CSV/Excel)
└── images/
    └── dashboard.png      # Dashboard screenshot
```

> Adjust the structure above to match the files you actually upload.

---

## ▶️ How to Use

1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/FinSight-Finance-Dashboard.git
   ```
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
3. Open `FinSight.pbix`.
4. Use the filters on the left to explore the data.

---

## 👤 Author

**Daniyal Hassan**
📧 Daniyalhassan901@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/your-profile) | [GitHub](https://github.com/your-username)

---

⭐ If you found this project useful, please give it a star!
