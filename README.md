# MS-Traveltide-final
Masterey Project on Masterschool / Final Exam Data of Traveltide

# 🌊 TravelTide Customer Segmentation & Rewards Analysis

Welcome to the TravelTide Data Analytics Project — an end-to-end SQL-powered analysis designed to support the launch of a targeted customer rewards program.

---

## 📌 Project Objective

Help TravelTide identify customer segments and assign the most appealing perk to each, in order to increase sign-up and engagement with the company’s upcoming **rewards program**.

All analysis is based purely on **SQL**. No Python or Jupyter was used.

---

## 🧠 Business Context

TravelTide is an e-booking startup with best-in-class travel inventory and aggregation tech. Since its launch in April 2021, it's grown rapidly. Marketing wants to personalize reward offers (like free checked bags, meals, or discounts) based on user behavior to increase conversion.

---

## 🗂️ Data Overview

The project uses data from 4 tables:

| Table      | Description                          |
|------------|--------------------------------------|
| `users`    | User demographics & sign-up info     |
| `sessions` | Booking and session activity logs    |
| `flights`  | Flight booking and trip details      |
| `hotels`   | Hotel booking details per trip       |

---

## 🛠️ Tools Used

- **PostgreSQL** (via Beekeeper Studio)
- **SQL** for all data transformations
- **Tableau** for final dashboarding
- **GitHub** for version control and documentation
- **PowerPoint** / **Google Slides** for final presentation

---

## 🧪 Project Phases

### 1. Data Exploration & Cleaning
- Investigated raw tables using SQL
- Cleaned and filtered sessions, removed invalid records
- Created a unified `session_level_enriched` table

### 2. Feature Engineering
- Built new metrics such as:
  - Booking frequency
  - Discount usage
  - Cancellation behavior
  - Perk-related indicators

### 3. Customer Segmentation
- Created behavioral segments using SQL logic (no ML)
- Assigned the best-fitting perk to each segment

### 4. Dashboard & Presentation
- Tableau dashboards built to visualize KPIs and clusters
- Final recommendations included tracking performance via CTR, sign-up conversion, and perk redemption rates

---

## 📈 Sample SQL Files

Located in `/sql/`, including:
- `01_exploration.sql`
- `02_cleaning_and_joins.sql`
- `03_feature_engineering.sql`
- `04_segmentation.sql`

---

## 📊 Dashboards

Screenshots or .twbx files available in `/dashboards/`  
Includes:
- Booking trends
- Customer segment profiles
- Perk match insights

---

## 🎯 Final Recommendations

- Use targeted perks to increase sign-up conversion
- Track effectiveness by cluster (A/B test emails)
- Update segments quarterly based on customer behavior

---

## 👤 Author

**[Robert Sch]**  
Data Analyst | SQL Enthusiast | Tableau Explorer  

---

