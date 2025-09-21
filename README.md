# FIFA Database Management System

**Database Management System for Women’s FIFA Tournament Statistics using MySQL and Python — includes ER diagram, schema design, views, indexes, triggers, OLAP queries, and window functions.**

---

## 📌 Overview
This project is a **database management system for Women’s FIFA Tournament Statistics**.  
It demonstrates **end-to-end database design and implementation**, covering schema modeling, data loading, optimization, and advanced analytics.  

The system manages information about **teams, players, venues, fixtures, matches, and goals**, with support for analytics through **OLAP queries and window functions**.

---

## ⚙️ Tech Stack
- **Database:** MySQL  
- **Programming Language:** Python  
- **Concepts & Features:** ERD, Relational Schema, DDL/DML, Views, Indexes, Stored Procedures, Triggers, Functions, OLAP, Window Functions  

---

## 🎯 Features
### 📊 Database Design
- **ER Diagram** with 7 entities (Team, Player, Matches, Venues, Goal, Fixture, PlayedBy)  
- **Relational Schema** with constraints and business rules  
- **Mock Data**: ≥15 records per relation  

### 🔍 Advanced SQL Implementation
- **Views** for team performance, player statistics, venue capacities, match results, upcoming fixtures  
- **Indexes** to speed up joins and searches (`TeamID`, `FIFARanking`, `PlayerID`, `City`)  
- **Temporary Tables** for match details, player achievements, and venue usage  
- **Stored Procedures & Functions** for rankings, player insertion, record cleanup, match counts, goal totals  
- **Triggers** to auto-update matches played and set default FIFA ranking  
- **Window Functions** for ranking players, running totals, and per-team aggregates  
- **OLAP Queries** with `ROLLUP`/`CUBE` for team stats, venue analysis, and performance reports  

