#  Banking-Data-Analytics

An end-to-end Banking Data Analytics project that simulates a realistic banking ecosystem using synthetic data generated with Python. The project demonstrates data engineering, SQL analysis, and business intelligence through an interactive Power BI dashboard.

---

##  Project Objectives

- Generate realistic banking datasets using Python
- Design relational banking tables with business rules
- Import and clean data in SQL Server
- Perform analytical SQL queries
- Build an interactive Power BI dashboard
- Showcase an end-to-end Data Analytics workflow

---

##  Tech Stack

- Python
- Pandas
- NumPy
- Faker
- SQL Server
- Power BI
- Git & GitHub

---

##  Dataset Overview

| Table | Records |
|--------|---------:|
| Customers | 30,000 |
| Accounts | 45,000 |
| Branches | 75 |
| ATMs | ~300 |
| Debit Cards | ~38,000 |
| Transactions | ~1,000,000 |

---

##  Repository Structure

```text
ATM-Transaction-Performance-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── sql/
├── powerbi/
├── images/
│
├── requirements.txt
├── LICENSE
└── README.md
```

---

##  Project Workflow

```
Python Data Generation
        │
        ▼
CSV Files
        │
        ▼
SQL Server
        │
        ▼
Data Cleaning
        │
        ▼
SQL Analysis
        │
        ▼
Power BI Dashboard
```

---

## Progress

### Data Generation

- [x] Customers
- [x] Accounts
- [x] Branches
- [x] ATMs
- [x] Debit Cards
- [x] Transactions

### SQL

- [ ] Database Design
- [ ] Data Import
- [ ] Data Cleaning
- [ ] 100+ SQL Queries

### Power BI

- [ ] Dashboard Design
- [ ] KPI Cards
- [ ] ATM Analytics
- [ ] Branch Analytics
- [ ] Transaction Analytics

---

##  Planned Dashboard KPIs

- Total Transactions
- Transaction Success Rate
- ATM Utilization
- Average Transaction Amount
- Branch Performance
- Monthly Transaction Trend
- Top Performing ATMs
- Transaction Type Distribution

---

## Large Dataset

The `transactions.csv` file (~200 MB) is not included in this repository because it exceeds GitHub's file size limit.

You can generate it by running:

- `notebooks/06_Transactions.ipynb`

or

- `python/transaction_generator.py`

The generated dataset contains approximately 1 million realistic banking transactions.
