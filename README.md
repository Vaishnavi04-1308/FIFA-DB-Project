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

### 🪟 Window Functions
- **`RANK()`** – rank players based on goals scored  
- **`ROW_NUMBER()`** – uniquely identify players or matches within partitions  
- **`DENSE_RANK()`** – handle ties in player goal rankings  
- **`NTILE()`** – split players into performance quartiles  
- **`LAG()` / `LEAD()`** – compare player/match performance across games  
- **Running totals with `SUM() OVER()`** – track cumulative goals or matches played  

### 📊 OLAP Queries
- Aggregations with **`ROLLUP`** for multi-level summaries (e.g., goals by team → by tournament)  
- Aggregations with **`CUBE`** for multidimensional analysis (e.g., venue usage by city and capacity)  
- Slice-and-dice reporting for player, team, and venue analytics  

