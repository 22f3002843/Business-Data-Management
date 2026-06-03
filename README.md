# Enhancing Operational Efficiency and Profitability Through Reliable Supply Solutions for Government and Private Entities

**BDM (Business Data Management ) Capstone Project Report**  


### 👤 Author Information
* **Student Name:** Devansh Gupta
* **Project Period:** April 2022 – March 2025 (Reports compiled in May/July 2025)

---

## 🏢 Executive Summary & Partner Organization

This capstone project focuses on the operational and financial optimization of **Rakhi Innovative Venture**, a B2B trading firm operating for over 10 years in Chowk, Kanpur, Uttar Pradesh. 

* **Business Segments:** Stationery, printing materials, office supplies, and general supplies.
* **Client Channels:** 
  * **Government & Public Sector (65–70% of business):** High-volume, tender-based, contract-driven orders with long payment cycles (e.g., defense-related factories, public departments).
  * **Private Sector (30–35% of business):** Local businesses, retail stores, clinics, and educational institutions placing smaller, ad-hoc orders.
* **Organization Structure:** Led by the owner and managed on-ground by Mr. Yogesh (Operational Manager) with a dedicated team of two staff members.

---

## ⚠️ Problem Statement & Business Challenges

The project aims to answer a core business question:
> *How can Rakhi Innovative Venture enhance operational efficiency and profitability through improved supply chain strategies, competitive pricing, and better financial management to secure market sustainability?*

To address this, the project identifies and solves three core bottlenecks:
1. **Supply Chain Inefficiencies:** Capital tied up in stagnant inventory, lack of structured reorder points, supplier dependency risks, and mismatches leading to off-season overstocking and peak-season stockouts of fast-moving items.
2. **Market Competition Challenges:** Extreme price competition from lower-cost vendors, lack of a digital footprint (like the Government e-Marketplace portal or business website), and high customer concentration risk.
3. **Cash Flow & Liquidity Difficulties:** Delays in payment clearances from government entities (ranging from 30 to 90 days), combined with highly volatile monthly sales revenue, causing severe working capital strain.

---

## 📥 Data Collection & Preprocessing

### 1. Data Collection Methods
Primary quantitative and qualitative data was gathered over two key on-site visits (January 25–30, 2025, and April 1–5, 2025) using:
* **Tally ERP Software exports** for transaction histories and financial records.
* **Physical registers & manual paper records** for daily sales order entries.
* **On-site interviews** and discussions with the Operational Manager, Mr. Yogesh, and administrative staff.

### 2. Preprocessing & Clean-up
To make the raw data suitable for analytical models, the following steps were taken:
* **Cleaning:** Removed duplicate records, resolved formatting issues, and cross-checked ledger values.
* **Standardization:** Normalized measurement units (e.g., `pcs`, `kg`, `sq. ft`, `ft`) across all inventory lines.
* **Categorization:** Classed the diverse product catalog into **six distinct segments**:
  1. **Printing** (Visiting cards, letterheads, duplex boards, customized branding)
  2. **Stationery** (Paper, files, folders, office pens)
  3. **Electronics** (Anti-virus licenses, computing accessories)
  4. **Household** (General utility goods)
  5. **Decor** (Corporate office decor items)
  6. **Construction** (Specialized supplies)
* **Workbook Structure:** Organized the data into 5 Excel sheets:
  * **`SALE`**: Daily sales transaction tracking.
  * **`PURCHASE`**: Vendor-side purchase details representing stock inflows.
  * **`Product Sales`**: Item-wise granular order quantities and transaction pricing.
  * **`Product Purchase`**: Item-wise vendor procurement cost tracking.
  * **`CLOSING STOCK`**: Instantaneous stock counts and valuation rates.

---

## 📊 Descriptive Statistics & Category Analysis

By summarizing three years of transactional records (April 2022 – March 2025), key descriptive metrics were calculated across all product categories:

| Product Category | Units Sold | Total Revenue (₹) | Avg Sales Value per Order (₹) | Avg Purchase Value per Order (₹) | Avg Profit per Order (₹) | Max Units in Single Order | Orders Received |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Printing** | 151,204 | 3,893,402.81 | 56,426.13 | 35,061.50 | **+21,364.63** | 8,000 | 69 |
| **Stationery** | 22,542 | 536,338.27 | 4,545.24 | 3,142.45 | **+1,402.79** | 12,000 | 118 |
| **Electronics** | 76 | 4,167.77 | 694.63 | 5,032.39 | **-4,337.76** | 50 | 6 |
| **Household** | 196 | 15,631.72 | 1,116.55 | 532.39 | **+584.16** | 50 | 14 |
| **Decor** | 8 | 3,004.00 | 1,001.33 | 633.33 | **+368.00** | 4 | 3 |
| **Construction** | 3 | 25,549.76 | 8,516.59 | 3,519.26 | **+4,997.33** | 3 | 3 |
| **TOTAL** | **174,029** | **₹4,464,094.33** | **-** | **-** | **-** | **-** | **213** |

*Note: Total purchases across categories amounted to ₹4,222,717.12, resulting in a net business profit of ₹241,377.21.*

### 🔍 Core Category Insights:
* **The Revenue Driver (Printing):** Represents **87.2%** of total sales revenue. It has the highest average profit margin per order (₹21,364.63), driven by institutional customization orders.
* **The High-Frequency Anchor (Stationery):** Generated the highest number of orders (118). It indicates consistent, repetitive demand but carries lower profit margins (₹1,402.79 per order).
* **The Profit Leak (Electronics):** Runs at a **negative average profit** (-₹4,337.76) per order. This signals pricing, supplier sourcing inefficiencies, or incorrect product-market positioning.
* **The High-Margin Niche (Construction):** Recorded a high average profit per order (₹4,997.33) despite very low volume (3 orders).

---

## 📈 Visualizations & Key Charts

The analysis includes nine primary visual charts that illustrate operational patterns:
1. **Monthly Units Sold by Category (Line Chart):** Illustrates demand timelines, showing the clear volume dominance of Printing and Stationery.
2. **Stock Value by Item (Bar Chart):** Details closing stock values, highlighting that Printed Visiting Cards (₹48,007.90 or ~35% of inventory), Duplex Board, and Coated Paper tie up the bulk of capital.
3. **Stock Value by Product Category (Pie Chart):** Summarizes capital allocation: Printing holds 66%, Stationery 33%, and Electronics 1%.
4. **Client-Wise Revenue (Horizontal Bar Chart):** Visualizes client concentration risk. **Rama Traders** is the top revenue generator, followed by Krishna Ultrasound and the Ordnance Equipment Factory.
5. **Sales Distribution by Product Category (Column Chart):** Represents total sales revenue, highlighting the steep skew towards Printing.
6. **Monthly Quantity Sold Trend (Line Chart):** Maps sales volatility, showcasing sharp peaks during government budget releases (March, June, December) and drops in holiday seasons (October, November).
7. **Revenue Growth Over Three Sessions (Bar Chart):** Compares monthly performance across FY 22-23, FY 23-24, and FY 24-25. It shows an upward trend with a major revenue spike in June 2024 (over ₹6.6 lakhs).
8. **Actual Revenue vs. Projected Sales Performance (Line Chart):** Shows the potential sales path under the 70% uplift model.
9. **Predicted Sales Trends with Risk Bounds (ETS Model Line Chart):** Plots future sales projections alongside confidence intervals.

---

## 🔮 Sales & Demand Forecasting

The project utilizes two analytical forecasting models to predict business growth and support working capital planning:

### 1. ETS (Exponential Smoothing) Forecasting Model
Using historical monthly sales revenue, the ETS model projects financial performance through early 2027:
* **Growth Trend:** Indicates steady upward growth, showing positive long-term business potential.
* **Upper Confidence Bound:** Under optimal operations (low collection delays, strong procurement), monthly revenue could exceed **₹700,000** by late 2026.
* **Lower Confidence Bound:** Dips below zero in low-season months, reflecting the revenue risks of relying on seasonal bulk orders.
* **Transitional Phase:** April to July 2025 is marked as a critical window where current sales trends start to deviate from historical baselines.

### 2. Manual Uplift Model (70% Projected Sales Simulation)
A simulation of revenue potential under optimized supply chain and cash flow conditions:
* **Uplift Factor:** A 70% growth rate was applied to historical monthly revenues.
* **Rationale:** Rooted in peak-performance months (June, September, December 2024), where revenue naturally grew between 65% and 75% due to bulk order execution and stock readiness.
* **Takeaway:** Demonstrates the revenue potential if the business maintains stock levels and stable working capital across all months, reducing off-season slumps.

---

## 📋 SWOT Analysis

A SWOT analysis outlines the strategic position of Rakhi Innovative Venture:

```
                  STRENGTHS                                      WEAKNESSES
┌──────────────────────────────────────────────┐┌──────────────────────────────────────────────┐
│ • Strong dominance in the printing segment.  ││ • Over-reliance on a few key clients (e.g.,  │
│ • Long-term trust with government entities.  ││   Rama Traders).                             │
│ • Proven capacity to handle large bulk orders││ • Low sales & visibility in minor categories.│
│ • Dual-channel model (public + private).     ││ • Lack of digital footprint & portal access. │
└──────────────────────────────────────────────┘└──────────────────────────────────────────────┘
                 OPPORTUNITIES                                    THREATS
┌──────────────────────────────────────────────┐┌──────────────────────────────────────────────┐
│ • Target mid-tier private clients (clinics,  ││ • Shifting of government departments to online│
│   schools) to reduce client concentration.   ││   procurement systems.                       │
│ • List products on the GeM portal.           ││ • Tender losses due to aggressive competitor │
│ • Cross-sell and bundle slow-moving items.   ││   pricing and price wars.                    │
│ • Revive Electronics with new supplier terms.││ • Delays in government payment approvals.    │
└──────────────────────────────────────────────┘└──────────────────────────────────────────────┘
```

---

## 💡 Strategic Recommendations

The project outlines actionable, data-backed recommendations across three areas:

### 📦 1. Supply Chain & Inventory Optimization
* **Monthly Sales-Purchase Tracker:** Set up a simple Excel tracker to monitor real-time stock levels, ensuring high-demand items are available during peak tender periods.
* **Demand-Based Procurement Calendar:** Schedule purchases of fast-moving items (Paper, Duplex Board) to align with historical demand peaks in March, June, and December.
* **Just-In-Time (JIT) for Slow Items:** Purchase items in low-demand categories (Electronics, Decor) only after receiving confirmed customer orders.
* **Backup Vendor Network:** Partner with 2–3 local backup suppliers to fulfill urgent, short-notice orders without carrying excess inventory.
* **Strategic Bidding Bundles:** Combine high-margin, slow-moving items with high-demand products in tender bids to clear stagnant stock.

### 📢 2. Market Expansion & Competitive Positioning
* **GeM Portal Onboarding:** Register on the **Government e-Marketplace (GeM)** portal to access public tenders more frequently and reduce reliance on local contracts.
* **Re-engage Inactive Accounts:** Reach out to old or inactive clients during low-demand months (October, November) and distribute a printed catalog or rate list.
* **Client Diversification:** Target private entities (schools, clinics, startups) to secure a more balanced revenue stream.
* **Feedback Loop:** Interview top clients to identify key selling points and refine marketing materials.

### 💸 3. Cash Flow & Working Capital Management
* **Cash Flow Calendar:** Use an Excel calendar to track expected receivables and incoming supplier payables, helping to anticipate liquidity gaps.
* **Reserve Sinking Fund:** Set aside a percentage of revenues during peak months (June, September, December) to cover fixed operational costs during lean months (October, November).
* **Early Payment Discounts:** Offer minor discounts (e.g., 1–2%) to private clients for early payments to boost cash flow.
* **Supplier Payment Alignments:** Negotiate longer credit terms with vendors to better align outgoing payments with government payment cycles.

---
© **2025 Devansh Gupta**. BDM Capstone Project.  
**Confidentiality Notice:** Contains real-world proprietary business data. Unauthorized copying or plagiarism is strictly prohibited.



