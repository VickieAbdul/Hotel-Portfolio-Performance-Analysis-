# Milton Hotels: Revenue, Operations & Cost Optimization Analysis

## Project Overview
This project analyzes operational, financial, guest experience, and energy data from the Milton Hotels global portfolio to understand how the company can grow revenue while keeping guests happy and costs under control.

The analysis is built around a real business tension that hotel groups face: pushing for revenue growth often raises concerns about operational strain, declining service quality, and rising energy costs. This project uses data to test whether those concerns are justified for Milton Hotels specifically.

---

## Business Problem
How can Milton Hotels increase revenue and guest satisfaction while controlling operational and energy costs across its hotel portfolio?

---

## Dataset Description
The dataset contains 7,600 daily hotel level records across a global portfolio including:

- Financial performance (ADR, RevPAR, total room revenue)
- Guest experience (satisfaction scores, complaint resolution time)
- Operational efficiency (check-in time, housekeeping turnover, staff to guest ratio)
- Sustainability metrics (energy consumption per room in kWh)

---

## Tools Used
- Python (Pandas, Matplotlib)
- Google Colab
- Power BI (for dashboarding and visualization)

---

## Analysis Structure

### 1. Data Cleaning & Preparation
- Standardized column names and date fields
- Removed invalid records and validated revenue calculations
- Created derived metrics including occupancy rate and revenue efficiency index

### 2. Exploratory Data Analysis (EDA)

#### EDA 4.1 — Revenue Structure
- Tested whether revenue is driven more by pricing (ADR) or demand (occupancy)
- ADR showed a 0.81 correlation with RevPAR while occupancy came in at 0.58, confirming pricing is the stronger lever

#### EDA 4.2 — Guest Satisfaction Drivers
- Examined whether operational pressure or high demand affects how guests feel about their stay
- Satisfaction scores showed near zero correlation with occupancy, housekeeping turnover time, and staffing ratios, suggesting service quality is consistent regardless of how busy hotels are

#### EDA 4.3 — Operational Efficiency
- Tested whether higher occupancy creates bottlenecks in check-in, housekeeping, or staffing
- Operational KPIs showed minimal sensitivity to occupancy levels, meaning the team scales effectively with demand

#### EDA 4.4 — Energy Efficiency
- Analyzed whether energy costs rise as hotels get busier or generate more revenue
- Energy consumption per room showed virtually no correlation with occupancy or RevPAR, indicating strong cost control already exists

---

## Key Insights
- Pricing strategy (ADR) is the primary driver of revenue, not how full hotels are.
- Guest satisfaction holds steady even when hotels are operating at high occupancy, meaning there is no quality versus volume tradeoff in this portfolio.
- Operations do not break down under demand pressure. Check-in times, housekeeping, and staffing all remain stable as occupancy rises.
- Energy costs are structurally flat. Revenue can grow without driving energy bills higher.
- The portfolio is performing in a balanced way but that also means there is likely untapped pricing upside that the data does not yet capture.

---

## Recommendations
- Invest in pricing optimization to drive revenue growth. ADR is the dominant lever and the data suggests Milton is not fully exploiting it.
- Raise occupancy targets with confidence. Guest satisfaction and operations both hold steady under pressure, so there is no data-backed reason to be conservative here.
- Avoid reactive spending on staffing or energy programmes. Both are already performing well and additional investment is unlikely to move the needle significantly.
- Segment the portfolio by ADR performance to identify which properties are pricing most effectively, then transfer those practices to underperforming hotels.

---

## Executive Conclusion
Milton Hotels is in a stronger position than the business question implies. The data shows that revenue growth is primarily a pricing problem, not an occupancy or capacity problem. Guest satisfaction is resilient, operations scale well with demand, and energy costs are already under control.

The clearest opportunity here is for Milton to get more aggressive and more precise with its pricing strategy. The operational foundation to support that growth already exists.

---

## Next Steps
- Perform hotel-level segmentation to identify high- and low-performing property clusters
- Conduct seasonal and regional performance analysis
- Explore predictive modeling for revenue and occupancy forecasting
---

## Author
**Victoria Abdul**  
Data Analyst | Python | PowerBI

- Email: victoria.j.abdulkadir@gmail.com
- LinkedIn: [linkedin.com/in/victoria-abdul](https://www.linkedin.com/in/victoriajabdul/)
- GitHub: [github.com/vickieabdul](https://github.com/vickieabdul)

---

## Dataset Disclaimer

**Status**: Fictitious / Synthetic

**Source**: Generated via Data Mockster (ChatGPT)

**Affiliation**: None. Any resemblance to real hotels is purely coincidental.
