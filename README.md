# Digital Payments Adoption in Europe
## What drives the shift away from cash?

An end-to-end data analysis exploring digital payment adoption across 30 European 
countries.

---

## Project Summary

Digital payment adoption in Europe averages 93.8% but varies significantly across 
countries — from Denmark at 100% to Romania at 63.5%. This project investigates 
what drives that variation and what it means for a fintech evaluating European 
expansion.

The analysis is structured in five parts:

1. **Data loading and cleaning** — three World Bank datasets merged into a unified dataframe
2. **Trend analysis** — evolution of adoption across 30 countries from 2014 to 2021
3. **Correlation analysis** — relationship between adoption, GDP per capita and internet penetration
4. **Clustering** — K-means segmentation of European countries into three strategic groups
5. **Actionable conclusions** — strategic briefing for a product team evaluating market entry

---

## Key Findings

- The European average rose from 83.5% in 2014 to 93.8% in 2021
- GDP per capita and internet penetration both correlate with adoption (r=0.58 and r=0.59), 
but neither explains it fully
- K-means clustering identifies three distinct market tiers: Mature Markets, Growing Markets 
and Emerging Markets
- Poland, Czechia and the Baltics emerge as the most attractive expansion targets — 
solid digital infrastructure, above-average adoption, lower competitive intensity

---

## Data Sources

| Dataset | Source | Link |
|---|---|---|
| Digital payment adoption | World Bank Global Findex Database 2025 | [Download](https://www.worldbank.org/en/publication/globalfindex/download-data) |
| GDP per capita | World Bank (NY.GDP.PCAP.CD) | [Download](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD) |
| Internet penetration | World Bank (IT.NET.USER.ZS) | [Download](https://data.worldbank.org/indicator/IT.NET.USER.ZS) |

---

## Tools

Python 3 — pandas, matplotlib, seaborn, scikit-learn
