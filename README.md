# Winlord del Oeste — Data Analyst Portfolio

## About

Hi, I'm Winlord, a data analyst based in Iloilo City, Philippines. I got into analytics because I've always been drawn to finding patterns in things and turning messy information into something that actually makes sense. I'm currently building my portfolio with real datasets, focusing on real estate and business performance analysis. I work with Excel, PostgreSQL, and Tableau Public.

📄 CV: *(coming soon)*
🔗 LinkedIn: [linkedin.com/in/winlordchristiandeloeste](https://linkedin.com/in/winlordchristiandeloeste)

---

## Table of Contents
- [About](#about)
- [Portfolio Projects](#portfolio-projects)
  - [Metro Manila Real Estate Analysis](#metro-manila-real-estate-analysis)
  - [Olist E-Commerce Performance Analysis](#olist-e-commerce-performance-analysis)
- [Certificates](#certificates)
- [Contact](#contact)

---

## Portfolio Projects

---

### Metro Manila Real Estate Analysis

**Repository:** [github.com/wdlweste/data-analytics-portfolio/tree/main/01_metro_manila_real_estate](https://github.com/wdlweste/data-analytics-portfolio/tree/main/01_metro_manila_real_estate)

**Business Question:** If a buyer has around ₱15 million to spend on a property in Metro Manila, which city gives the best value — and what would they actually get for that budget?

**Description:** Analyzed 1,000+ Philippine real estate listings scraped from lamudi.com.ph. Started by parsing a combined location field using Text to Columns, filtered down to Metro Manila cities, then applied a ₱13M–₱17M price band. Built pivot tables comparing average floor area, bedrooms, bathrooms, and price per sqm across cities. Applied sample size validation before drawing any conclusions — cities with fewer than 10 listings were flagged as directional only.

**Tools:** Microsoft Excel — Text to Columns, Number Filters, Pivot Tables, AVERAGEIF/AVERAGEIFS, calculated columns, bar charts

**Skills:** Data cleaning, filtering, aggregation, sample size validation, data visualization

**Key Findings:**
- Pasig is the most data-reliable city (n=183) — buyers get ~57 sqm at ₱15.7M average, with a price per sqm of ₱277,020
- Pasay shows the best price per sqm (₱188,944) and largest average floor area (86 sqm), though sample size (n=7) limits confidence
- Quezon City offers a balanced option — 70 sqm at ₱14.5M average (n=13, directional)
- Location tagging inconsistencies were found and corrected during cleaning (e.g. San Juan, Batangas mislabeled as Metro Manila)

**Recommendations:**
- Buyers prioritizing reliable market data should focus on Pasig — the sample is large enough to trust, and the price is consistent with mid-range Metro Manila condo units
- Pasay and Quezon City are worth monitoring for better value, but require more data before making a confident recommendation
- A follow-up analysis with a larger dataset or wider price band would help validate the Pasay signal before acting on it

---

### Olist E-Commerce Performance Analysis

**Repository:** [github.com/wdlweste/data-analytics-portfolio/tree/main/02_olist_ecommerce](https://github.com/wdlweste/data-analytics-portfolio/tree/main/02_olist_ecommerce)

**Dashboard:** [Olist E-Commerce Performance Dashboard](https://public.tableau.com/app/profile/winlord.del.oeste/viz/OlistE-CommercePerformanceDashboard_17845301007780/Dashboard1)

**Business Questions:**
1. Which product categories generate the most revenue?
2. Does late delivery hurt customer review scores?
3. Which states have the most customers, and how much do they spend per order?

**Description:** Built a 9-table PostgreSQL relational database from the Olist Brazilian e-commerce dataset (~100,000 orders, 2016–2018). Wrote multi-table SQL JOIN queries filtered to delivered orders only, then exported results as CSVs and visualized them in an interactive Tableau Public dashboard — combining a revenue ranking chart, delivery performance comparison, and a Brazil state-level choropleth map.

**Tools:** PostgreSQL, Tableau Public

**Skills:** Database setup, multi-table JOINs, CASE statements, aggregate functions, filtering, CSV export, interactive dashboarding, geographic mapping

**Key Findings:**
- Health & beauty leads all categories with R$1.23M revenue — nearly R$70K ahead of second place (watches & gifts)
- Late deliveries average a 2.57 review score vs. 4.29 for on-time — a 1.72-point drop on a 5-point scale
- São Paulo accounts for 46,448 orders (almost 3x second place Rio de Janeiro) but has the lowest average spend per order among top states

**Recommendations:**
- Invest in health & beauty and watches & gifts inventory — both consistently outperform other categories and are worth prioritizing for promotions and stock depth
- Delivery time is the single biggest driver of poor reviews — improving logistics in high-volume states (SP, RJ, MG) would have the most direct impact on customer satisfaction scores
- São Paulo's high volume but low spend per order suggests a price-sensitive customer base — bundling or volume promotions may be more effective there than premium product pushes

---

## Certificates

- Google Data Analytics Professional Certificate (Jun 2026) — Coursera / Google

---

## Contact

- LinkedIn: [linkedin.com/in/winlordchristiandeloeste](https://linkedin.com/in/winlordchristiandeloeste)
- GitHub: [github.com/wdlweste](https://github.com/wdlweste)
