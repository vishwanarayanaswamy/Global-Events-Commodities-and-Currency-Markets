# Global-Events-Commodities-and-Currency-Markets
# Global Events, Commodities and Currency Markets
### Applied Data Analytics and Market Research Assignment

---

## Project Overview

This project is a data-driven market research study conducted as part of the Data Science for Business (DSB) course. Working as simulated junior market analysts, the team analyses historical commodity prices (Brent Oil, Gold, Silver) and global currency payment data to identify patterns, connect them to major geopolitical and economic events, and deliver practical business recommendations.

The final output is a professional report (8–10 pages) combining data analytics, data visualisation, and market research narrative targeted at a non-technical business audience.

---

## Team

| # | Name | Role | Part I Tasks |
|---|------|------| ------------ |
| 1 | Khurshid Normurodov | Team Leader | Overall coordination, report structure, Section E (Comparison E25–E30) + Final Recommendation |
| 2 | Dinesh Reddy Mallela | Data Analyst | Section A — Data Preparation & Understanding (A1–A5): date ranges, row counts, missing values, date formatting, Swift metrics
| 3 | Nischitha Purushotham | Descriptive Analytics | Section B — Descriptive Analytics (B6–B12): highest/lowest prices, annual averages, top 5 years for Oil, Gold, Silver |
| 4 | Vishwa Narayanaswamy | Visualisation Specialist | Section C — Trend & Visual Analytics (C13–C18): line charts, combined Gold/Silver chart, bar chart, latest values table |
| 5 | Sampath Reddy Nimmareddy | Currency Analyst | Section D — Currency Tracker Analytics (D19–D24): top currencies, USD/RMB share & rank, offshore RMB data, bar chart |

---

## Business Scenario

> You are working as a junior market analyst for a financial research team. The team wants a simple but clear report showing how commodity prices and currency indicators changed over time. Your report should not only show charts and numbers — it should also explain whether major global events may have influenced oil, gold, silver and currency market behaviour. The final recommendation should be written for a non-technical manager who wants to understand risk, opportunity and market direction.

---

## Datasets

All four datasets are provided in the project `/datasets` directory.

| File | Date Range | Rows | Key Fields |
|------|-----------|------|-----------|
| `Brent Oil.csv` | Jan 1946 – Mar 2026 | 962 | `Date`, `Value` (USD/barrel) |
| `Gold 100years.csv` | Jan 1915 – Apr 2026 | 1,335 | `Date`, `Value` (USD/troy oz) |
| `silver 100 years.csv` | Jan 1915 – Apr 2026 | 1,335 | `Date`, `Value` (USD/troy oz) |
| `swift_currency_tracker_all_reports.csv` | Dec 2025 – Feb 2026 (4 reports) | 330 | `report_month`, `data_month`, `metric`, `category`, `currency_or_economy`, `value`, `unit`, `rmb_global_rank` |
| `global-currency-tracker-april-2026.pdf` | April 2026 | — | Reference report for Part II context |

### Swift Currency Tracker — Available Metrics

| Metric | Category |
|--------|----------|
| Global Payment Share | Currency Ranking |
| International Payment Share (ex-Eurozone) | Currency Ranking |
| Trade Finance Share | Currency Ranking |
| Offshore RMB by Economy | Offshore Economies |
| FX Spot Currency Ranking | FX Spot |
| FX Spot Economies (RMB) | FX Spot |
| RMB MoM Payment Growth | RMB Activity |
| All Currencies MoM Payment Growth | Market Activity |

---

## Assignment Structure

The assignment has two parts with a minimum requirement for each.

---

## Part I — Data Analytics Component

**Minimum requirement:** Answer at least **10 questions**, with at least one from each of the four sections below.

### A. Data Preparation and Understanding
*(Assigned to: Dinesh Reddy Mallela)*

| Q | Question | Expected Output |
|---|----------|----------------|
| A1 | What is the start date and end date in each dataset? | Data summary table |
| A2 | How many rows are in each dataset? | Data summary table |
| A3 | Are there missing values or repeated dates? | Data quality table |
| A4 | Convert Date to proper format; create Month and Year columns for commodity datasets | Cleaning note |
| A5 | Identify the main metrics in the Swift dataset | Short list or table |

### B. Descriptive Analytics
*(Assigned to: Nischitha Purushotham)*

| Q | Question | Expected Output |
|---|----------|----------------|
| B6 | Highest and lowest Brent Oil prices and years | Summary table |
| B7 | Highest and lowest Gold prices and years | Summary table |
| B8 | Highest and lowest Silver prices and years | Summary table |
| B9 | Average price by year for Brent Oil, Gold and Silver | Annual average table |
| B10 | Top 5 years by highest average Brent Oil price | Top-5 table |
| B11 | Top 5 years by highest average Gold price | Top-5 table |
| B12 | Top 5 years by highest average Silver price | Top-5 table |

### C. Trend and Visual Analytics
*(Assigned to: Vishwa Narayanaswamy)*

| Q | Question | Expected Output |
|---|----------|----------------|
| C13 | Line chart — Brent Oil over time with interpretation | Chart + 3–5 lines |
| C14 | Line chart — Gold over time with interpretation | Chart + 3–5 lines |
| C15 | Line chart — Silver over time with main peaks | Chart + 3–5 lines |
| C16 | Combined Gold + Silver chart with comparison | Combined chart |
| C17 | Bar chart — average annual Brent Oil (last 10 years) | Bar chart |
| C18 | Table of latest available values for all three commodities | Latest values table |

### D. Currency Tracker Analytics
*(Assigned to: Sampath Reddy Nimmareddy)*

| Q | Question | Expected Output |
|---|----------|----------------|
| D19 | Top currencies by global payment share (most recent month) | Ranking table |
| D20 | USD share in most recent global payment data | Short answer |
| D21 | CNY/RMB share and rank in most recent global payment data | Short answer |
| D22 | Currencies appearing most often in the top 5 across reports | Count table |
| D23 | Offshore RMB economy with highest share | Short answer |
| D24 | Bar chart — top 10 currencies from one selected month | Bar chart |

### E. Simple Comparison Questions
*(Assigned to: Khurshid Normurodov — Team Leader)*

| Q | Question | Expected Output |
|---|----------|----------------|
| E25 | Latest Gold vs. long-term average — above or below? | Comparison table |
| E26 | Latest Brent Oil vs. long-term average — above or below? | Comparison table |
| E27 | Which commodity has the largest price swings? | Chart or summary table |
| E28 | One year with strong oil movement — did Gold/Silver also move? | Comparison paragraph |
| E29 | Dashboard with 4–6 visuals of key findings | Dashboard page |
| E30 | Three manager-friendly insights | Three bullet points |

### Optional Bonus Questions

| # | Question |
|---|----------|
| B1 | Monthly/yearly percentage change for Gold, Silver and Brent Oil |
| B2 | Correlation table between Gold, Silver and Brent Oil (annual averages) |
| B3 | Heat map from correlation table |
| B4 | Scatter plot comparing Gold and Silver annual averages |
| B5 | Moving average line on Gold or Brent Oil trend |
| B6 | Simple trendline forecast (clearly labelled as estimate only) |

---

## Part II — Market Research Component

**Minimum requirement:** Answer at least **4 questions** from Part II. Answers must reference evidence from provided files and link to at least one chart or table from Part I.

Key global events to research and connect to data:
- Strait of Hormuz crisis / shipping disruption
- Energy supply shocks
- Gold accumulation by central banks
- Western sanctions and counter-sanctions
- Tariff discussions and trade policy shifts
- BRICS Pay and alternative settlement systems
- USD dominance vs. RMB internationalisation

### A. Event Identification

| Q | Question | Expected Output |
|---|----------|----------------|
| II-A1 | Three major global events affecting commodity or currency markets | Evidence-based paragraph |
| II-A2 | Timeline of selected events (Hormuz, sanctions, BRICS Pay, gold accumulation, etc.) | Timeline table |
| II-A3 | Which event is most directly connected to Brent Oil prices? | Short paragraph + chart link |
| II-A4 | Which event is most directly connected to Gold or Silver prices? | Short paragraph + chart link |

### B. Linking Events to Commodity Data

| Q | Question | Expected Output |
|---|----------|----------------|
| II-B5 | How could an oil supply shock affect Brent Oil prices? | Explanation + Brent chart |
| II-B6 | Why might Gold increase during geopolitical uncertainty? | Explanation + Gold chart |
| II-B7 | Is Silver behaving as a precious metal or industrial commodity? | Comparison paragraph |
| II-B8 | Compare Oil, Gold and Silver during one chosen crisis period | Comparison table |

### C. Linking Events to Currency Data

| Q | Question | Expected Output |
|---|----------|----------------|
| II-C9 | How does the tracker show USD's role in international payments? | Paragraph + value/ranking |
| II-C10 | What does the tracker show about CNY/RMB's role? | Paragraph + value/ranking |
| II-C11 | Why do sanctions and BRICS Pay matter for currency analysis? | Evidence-based paragraph |
| II-C12 | What does offshore RMB data say about Hong Kong and other centres? | Paragraph + value/ranking |

### D. Business Interpretation and Recommendation

| Q | Question | Expected Output |
|---|----------|----------------|
| II-D13 | Which market is most sensitive to global events? | Argument + chart/table |
| II-D14 | Risk note for a company exposed to oil prices | 100–150 words |
| II-D15 | Risk note for a company holding USD, Gold or RMB assets | 100–150 words |
| II-D16 | Three practical recommendations for investors/companies/policymakers | Three recommendations |

---

## Report Structure

| Section | Content |
|---------|---------|
| 1. Introduction | Purpose of the assignment and datasets used |
| 2. Data Overview | File descriptions, date ranges, variables, cleaning steps |
| 3. Data Analytics Findings | Main tables and charts from Part I with clear explanations |
| 4. Market Research Findings | Selected global events connected to data patterns |
| 5. Final Recommendation | Business-style conclusion with 3 practical recommendations |
| 6. Appendix | Extra tables, screenshots, calculation notes, optional bonus work |

**Suggested length:** 8–10 pages (excluding appendix)

---

## Submission Items

- [ ] Report file (PDF or Word)
- [ ] Spreadsheet workbook (Excel or equivalent)
- [ ] Optional: 3–5 slide summary presentation
- [ ] At least 10 Part I questions answered (one from each section A–D minimum)
- [ ] At least 4 Part II questions answered
- [ ] All charts included with labelled titles and axis names
- [ ] Summary tables included
- [ ] Final dashboard or summary page included
- [ ] Global events discussed and connected to data
- [ ] Final recommendation written in plain business language

---

## Marking Rubric

| Criteria | Weight | What Is Assessed |
|----------|--------|-----------------|
| Data preparation and understanding | 15% | Correct use of datasets, date handling, data quality checks |
| Charts, tables and descriptive analytics | 30% | Clear visuals, correct calculations, meaningful trend descriptions |
| Currency tracker analysis | 15% | Payment shares, currency rankings, offshore RMB interpretation |
| Market research connection | 25% | Clear link between global events and observed market behaviour |
| Final recommendation and communication | 15% | Professional writing, practical recommendations, organised structure |

---

## Task Assignment Summary

| Member | Responsibility | Part I Section | Part II Focus |
|--------|---------------|---------------|--------------|
| Khurshid Normurodov (Leader) | Coordination, report structure, final review | Section E (Q25–30) | D — Business Interpretation & Recommendation |
| Dinesh Reddy Mallela | Data cleaning and preparation | Section A (Q1–5) | A — Event Identification |
| Nischitha Purushotham | Descriptive statistics and summaries | Section B (Q6–12) | B — Linking Events to Commodity Data |
| Vishwa Narayanaswamy | Data visualisation and trend charts | Section C (Q13–18) | B — Linking Events to Commodity Data |
| Sampath Reddy Nimmareddy | Currency tracker analysis | Section D (Q19–24) | C — Linking Events to Currency Data |

---

## Suggested Tooling

- **Python** (pandas, matplotlib/seaborn, plotly) or **Excel/Google Sheets** for data work
- **Word / Google Docs** for the report
- **PowerPoint / Google Slides** for the optional summary presentation
- **MS Teams** for collaboration and file sharing

---

## Key Global Context (for Part II Reference)

- **Strait of Hormuz tensions** — directly affect oil supply routes and Brent prices
- **Central bank gold accumulation** (Russia, China, emerging markets) — drives long-term gold demand
- **Western sanctions on Russia (2022+)** — disrupted energy markets, accelerated de-dollarisation discussions
- **BRICS Pay / mBridge** — alternative cross-border settlement systems bypassing SWIFT
- **USD vs. RMB in global payments** — USD holds ~50% global payment share; RMB share growing but below 5%
- **Tariff escalations (2024–2025)** — U.S.–China trade tensions affecting commodity and FX markets

---

*Assignment: Data Science for Business (DSB) | Team of 5 | Report length: 8–10 pages*
