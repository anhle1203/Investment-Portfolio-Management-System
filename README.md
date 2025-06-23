# Investment Portfolio Management System

A capstone project for Database Administration class at TCU (COSC 30603) reflecting a comprehensive structure of a relational database at buy-side firms. It models an investment management platform where users can create, store, and analyze portfolios using both statistical methods and SQL-driven data pipelines.

---

## Project Overview

This system is designed to simulate how real-world investment firms might manage portfolios. It includes:

- **Database Schema & SQL Scripts** for storing investor profiles, trades, assets, and historical prices   
- **Synthetic Financial Data** for demonstration and testing  
- **Documentation** detailing the system's architecture and schema
- (Incoming) Modern Portfolio Theory Optimization implemented in Python

---

## Repository Structure
``` bash
Investment-Portfolio-Management-System/
│
├── Data/                       # Contains synthetic sample data (.csv)
├── Everything.sql              # Full schema & SQL statements for database creation
├── Schema.pdf                  # ER diagram and schema design documentation
├── Database Final Project.pdf  # Final project report with system design overview
├── optimization.py             # (Incoming...) Python logic for portfolio optimization
└── README.md                   # Project overview and setup
```

---

## Database Highlights

- **Entities Modeled:** Investors, Assets, Market, Transactions, Price History, Risk/Performance Metrics
- **Core Functionalities:**
  - Create and manage portfolios
  - Record trades and track returns
  - Analyze historical asset performance
- **Normalization:** Designed to 3NF for efficiency and data integrity  
- **Scalability:** Easily extendable to support real-time trading and user authentication

---

## Use Cases
1. Academia – As references for database and finance coursework

2. Quantitative Finance Practice - Explore asset allocation, optimization, and risk metrics

3. End-to-End Portfolio Simulation - Simulate full investment workflows from schema to strategy

---

## Consideration
This project is for academic and personal use only. Feel free to fork and extend.
