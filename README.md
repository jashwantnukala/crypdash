<div align="center">

# CRYPDASH 2020
## Crypto Market Analytics Dashboard

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=00E07A&center=true&vCenter=true&width=600&lines=Crypto+Market+Analytics;Full+Year+2020+·+20+Coins+·+6,708+Records;Interactive+Web+Dashboard;Built+with+HTML+%2B+CSS+%2B+Chart.js" alt="Typing SVG" />

<br/>

[![Live Demo](https://img.shields.io/badge/Live%20Demo-CRYPDASH-00e07a?style=for-the-badge&logoColor=white)](https://jashwantnukala.github.io/crypdash/)
[![Data Source](https://img.shields.io/badge/Data-CoinGecko%202020-2196f3?style=for-the-badge)](https://www.coingecko.com/)
[![Made With](https://img.shields.io/badge/Made%20with-HTML%20%2B%20CSS-ffc107?style=for-the-badge)](https://jashwantnukala.github.io/crypdash/)
[![Excel](https://img.shields.io/badge/Tool-MS%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://jashwantnukala.github.io/crypdash/)
[![Chart.js](https://img.shields.io/badge/Charts-Chart.js-ff6384?style=for-the-badge)](https://www.chartjs.org/)
[![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white)](https://jashwantnukala.github.io/crypdash/)

<br/>

> ### Live Dashboard: [https://jashwantnukala.github.io/crypdash/](https://jashwantnukala.github.io/crypdash/)

<br/>

</div>

---

<div align="center">

## Dashboard Preview

[![CRYPDASH Dashboard](https://img.shields.io/badge/Click%20to%20View%20Live%20Dashboard-00e07a?style=for-the-badge)](https://jashwantnukala.github.io/crypdash/)

*An interactive single-page analytics dashboard for the 2020 Crypto Market*

</div>

---

## Project Overview

> The cryptocurrency market generates enormous volumes of data every day — prices, volumes, market caps, and returns shift constantly. Analyzing such datasets manually is nearly impossible without proper tooling and visualization.

**CRYPDASH 2020** transforms raw **CoinGecko historical data** into a fully interactive analytics experience — covering **20 cryptocurrencies**, **6,708 daily records**, and **12 months** of the most volatile year in recent crypto history.

### What This Dashboard Covers

| Area | Details |
|---|---|
| Coin ROI | Full-year return on investment for all 20 coins |
| Risk Analysis | Volatility, std deviation, risk classification |
| Market Phases | Bull Run → COVID Crash → Recovery → Year-End Rally |
| Monthly Trends | Return, volume, best & worst coin per month |
| Coin Comparison | Side-by-side stats across all 20 cryptos |
| Price Ranges | Year high, avg, and low for every coin |

---

## Problem Statement

Raw cryptocurrency data is:

- Large and complex — thousands of daily records across many coins
- Hard to compare — prices range from $0.001 to $20,000+
- Easy to misread — without context, numbers are meaningless
- Full of hidden patterns — trends invisible without visualization

This project solves all of that by building a system that can:

```
✓  Collect & Clean      →   Raw CoinGecko data organized & structured in Excel
✓  Analyze              →   ROI, volatility, risk scores computed
✓  Visualize            →   9 Chart.js charts + custom UI components
✓  Present              →   Fully interactive single-page dashboard
```

---

## Objectives

- [x] Collect and organize 6,708 daily OHLCV records across 20 coins
- [x] Clean and preprocess the dataset using MS Excel
- [x] Identify KPIs — ROI, avg return, std deviation, volatility, market cap
- [x] Analyze individual coin performance across the full year
- [x] Study market phases and their impact on coin behavior
- [x] Build a fully interactive, theme-switchable web dashboard
- [x] Deploy the dashboard live on GitHub Pages

---

## Dataset Description

<div align="center">

| Property | Details |
|---|---|
| Source | CoinGecko Historical API |
| Year | 2020 (Full Calendar Year) |
| Type | Daily OHLCV (Open, High, Low, Close, Volume) |
| Records | 6,708 daily entries |
| Coins | 20 major cryptocurrencies |
| Preprocessing Tool | Microsoft Excel |

</div>

### Dataset Fields

```
Dataset
├── Date
├── Coin Name & Ticker
├── Open / High / Low / Close Price
├── Daily Volume
├── Market Capitalization
└── Derived: ROI · Avg Return · Std Dev · Volatility · Risk Level · Signal
```

---

## Tools & Technologies

<div align="center">

| Tool | Purpose |
|---|---|
| ![Excel](https://img.shields.io/badge/MS%20Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white) | Data Cleaning, Preprocessing & KPI Calculation |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Dashboard Structure & Markup |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Styling, Theming, Animations & Layout |
| ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white) | All 9 Data Visualizations |
| ![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=flat-square&logo=google&logoColor=white) | Typography (Syne, Space Mono) |
| ![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=github&logoColor=white) | Live Deployment |

</div>

### Key Techniques Used

- Data Cleaning & Normalization (MS Excel)
- ROI & Average Return Calculation
- Statistical Analysis — Std Deviation & Daily Volatility
- Risk Classification (Low / Medium / High)
- Investment Signal Generation (Strong Buy / Buy / Hold / Avoid)
- CSS Custom Properties for dual Dark / Light theming
- CSS Grid & `clamp()` for fully responsive layouts
- Animated counters, ticker scroll, and fade-up animations
- Log-scale price range visualization
- Sortable tables with multi-key comparisons

---

## Key Performance Indicators (KPIs)

<div align="center">

| KPI | Value |
|---|---:|
| Total Daily Records | 6,708 |
| Cryptocurrencies Tracked | 20 |
| Best ROI 2020 | +9.98x (Chainlink) |
| Worst ROI 2020 | 0.07x (USD Coin) |
| Average Daily Return | +0.39% |
| Total Market Phases | 4 |
| Biggest Single-Month Drop | −0.55% (March — COVID Crash) |
| Biggest Single-Month Gain | +1.43% (January — Bull Run) |

</div>

---

## Charts & Visualizations

The dashboard features 9 Chart.js charts plus custom-built HTML/CSS components:

```
Visualizations
├── Horizontal Bar    →  ROI for all 20 coins (sorted)
├── Horizontal Bar    →  Avg daily volatility per coin
├── Area Line         →  Monthly avg close price trend
├── Multi-line        →  Top 5 coins monthly return comparison
├── Bar (Green/Red)   →  Avg daily return per month
├── Bar (Gradient)    →  Total market volume per month
├── Scatter Plot      →  Risk vs. Return for all 20 coins
├── Doughnut          →  Risk level distribution
├── Doughnut          →  Market cap share (top 7 + others)
└── Custom Range Bars →  Year High / Avg / Low (log scale)
```

---

## Analysis Performed

### ROI Analysis

- Calculated full-year return on investment for all 20 coins
- Ranked coins from best to worst performer
- Top 5: Chainlink · NEM · Cardano · Stellar · CRO

### Risk & Return Analysis

- Computed standard deviation and daily volatility per coin
- Classified coins into Low / Medium / High Risk categories
- Assigned investment signals: Strong Buy · Buy · Hold · Avoid

### Market Phase Analysis

| Phase | Period | Avg Daily Return | Characteristic |
|---|---|---|---|
| Bull Run | Jan – Feb | +0.770% | Pre-COVID Rally |
| COVID Crash | March | −0.546% | Market Collapse |
| Recovery | Apr – Aug | +0.575% | Gradual Stabilisation |
| Year-End Rally | Sep – Dec | +0.191% | BTC hits All-Time High |

### Monthly Analysis

- Tracked avg daily return per month
- Identified best and worst performing coin each month
- Compared total market volume across all 12 months

### Full Coin Comparison

- Side-by-side comparison of all 20 coins across 10+ metrics
- Sortable by any column, filterable by recommendation signal or risk level

---

## Dashboard Features

```
Interactive Dashboard
├── Dark & Light Mode Toggle
├── Live Coin Search Bar
├── Recommendation Filter Buttons
│   (Strong Buy / Buy / Hold / Avoid / Low Risk / High Risk)
├── Scrolling Live Ticker (all 20 coins)
├── KPI Cards with Animated Counters
├── Top 5 Performers Badges
├── Sortable Investment Leaderboard
├── Coin Detail Modal (click any coin)
│   └── 9 stat cards + monthly sparkline chart
├── Market Phase Summary Cards
├── Monthly Breakdown Table
├── Price Range Visualization (log scale)
└── Full 20-Coin Sortable Comparison Table
```

---

## Key Insights

> **Chainlink (LINK)** delivered the highest ROI of 2020 at an extraordinary 9.98x

> **The COVID Crash (March 2020)** caused the steepest avg daily return of −0.55%, wiping gains across all coins

> **The Year-End Rally** saw Bitcoin hit its then all-time high, driven by institutional adoption

> **Bitcoin & Wrapped Bitcoin** (Low Risk) offered the most stable, predictable return profiles

> **Stablecoins** (Tether, USD Coin) served as useful 0-volatility benchmarks for risk comparison

> **Higher avg daily return consistently correlated with better full-year ROI** — sustained momentum matters more than single spike events

---

## Conclusion

CRYPDASH 2020 successfully transformed raw CoinGecko historical data into a rich, interactive analytics experience.

### It helped in:

- Understanding the importance of Data Analytics in Finance & Crypto
- Leveraging MS Excel for effective data cleaning and KPI extraction
- Building a framework-free web dashboard with production-grade quality
- Making complex crypto data accessible and explorable for any audience

This project demonstrates how data analytics can support smarter investment decision-making in modern financial markets.

---

## Team

<div align="center">

| Name | Email |
|---|---|
| Jashwant Nukala | jashwantnukala2025.comp@mmcoe.edu.in |
| Aarushi Patil | aarushipatil2025.comp@mmcoe.edu.in |
| Sanjana Nandani | sanjananandani2025.comp@mmcoe.edu.in |
| Ganesh Padme | ganeshpadme2025.comp@mmcoe.edu.in |

*MMCOE · Computer Engineering · Batch of 2025*

</div>

---

## Future Scope

- Live API Integration — Real-time CoinGecko prices & market data
- Python Analytics — Advanced statistical modelling & backtesting
- Machine Learning — Predictive coin performance models
- Portfolio Simulator — Custom investment allocation & returns tool
- Multi-Year Comparison — Extended 2018 → 2024 dataset
- Power BI / Tableau — Enterprise-grade BI version of the dashboard

---

<div align="center">

---

## View the Live Dashboard

### [https://jashwantnukala.github.io/crypdash/](https://jashwantnukala.github.io/crypdash/)

<br/>

*Built with care by Team CRYPDASH · MMCOE Computer Engineering · 2025*

---

If you found this project useful, please give it a star!

<br/>

# Thank You

</div>
