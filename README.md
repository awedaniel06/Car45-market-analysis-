# 🚗 Nigeria Used Car Market Analysis — Power BI Dashboard

A comprehensive Power BI dashboard analyzing the Nigerian used car market using listing data from **Cars45**, covering pricing trends, supply distribution, and vehicle characteristics across 1,722 listings.

This project examines how price and supply behave across selling condition, manufacturer, mileage, year of manufacture, and colour — revealing a market dominated by used vehicles, with distinct positioning strategies across brands (scale vs. premium exclusivity vs. balanced positioning).

---

## 📊 Project Overview

This project explores pricing and supply dynamics in Nigeria's automotive resale market, helping answer key questions such as:

- How does selling condition (Brand New, Imported, Registered) affect price?
- Which car makers command the highest and most frequent listings?
- How do mileage and year of manufacture influence pricing?
- What does the overall supply landscape look like by brand, color, and mileage category?

The dashboard is built with **Power BI Desktop** and split into two main views: **Price Analysis** and **Supply Analysis**.

---

## 🔑 Key Metrics

| Metric | Value |
|---|---|
| Total Number of Cars | 1,722 |
| Average Car Price | ₦15.28M |
| Average Price — Registered | ₦10.14M |
| Average Price — Imported | ₦25.06M |
| Average Price — Brand New | ₦34.13M |
| Registered Vehicles | 65.68% |
| Imported Vehicles | 34.09% |
| Brand New Vehicles | 0.23% |

---

## 📈 Dashboard 1: Price Analysis

- **Price by Selling Condition** — Brand New, Imported, and Registered cars compared
- **Price by Maker** — Top makers by price include Tesla, Rover, Dongfeng, Porsche, Changan, Mercedes-Benz, Land Rover, GAC, and Genesis
- **Price by Mileage Category** — Low, Light Used, Average Used, High Mileage, and Very High Mileage
- **Price by Year of Manufacture** — Pricing trends from 1990 to 2025

## 📦 Dashboard 2: Supply Analysis

- **Total Number by Selling Condition** — Registered listings dominate supply
- **Total Number by Maker** — Toyota, Lexus, Mercedes-Benz, Honda, Hyundai, Ford, Nissan, Kia, and Acura lead by volume
- **Total Number by Mileage Category** — Distribution across mileage bands
- **Total Number by Year of Manufacture** — Volume trends from 1990 to 2025
- **Total Number by Colour** — Black, Gray, Silver, Blue, White, Red, Gold, Green, and Burgundy

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Data modeling, DAX measures, and interactive dashboard design
- **Data Source** — Cars45 used car listings (Nigeria)

---

## 💡 Key Insights

- **Price vs. condition**: Brand new vehicles make up a negligible share of supply (0.23%, ~4 listings) but command the highest average prices (₦34.13M) — a gap of roughly ₦24M over registered vehicles, making condition one of the strongest price drivers in the market.
- **Used-vehicle dominance**: Registered (locally used) vehicles form the bulk of supply (65.68%) at the most affordable average price point, meaning the market is 99.77% used vehicles by volume.
- **Price leaders ≠ volume leaders**: Premium and niche makers (Tesla, Porsche, Mercedes-Benz, Land Rover, Genesis) drive the highest price points, while an almost entirely different set of mainstream brands (Toyota, Lexus, Honda, Hyundai, Ford) dominate by volume — a "Price by Maker" ranking should never be read as a popularity ranking.
- **Depreciation curve**: Mileage and year of manufacture show a clear inverse relationship with price — low-mileage, newer vehicles command the highest prices — yet supply is skewed toward the higher-mileage end, meaning most available vehicles sit in the lowest-priced tier.
- **Brand positioning**: Toyota leads on scale/accessibility (600+ listings), Tesla anchors the premium extreme (~₦100M average), and Lexus achieves a rarer balance of pricing power with broad accessibility.
- **Sweet spot segment**: The 2005–2015 manufacture band shows the highest listing concentration combined with moderate pricing, positioning it as the market's practical sweet spot; post-2020 vehicles show the opposite pattern — high price, thin supply.
- **Consumer preference**: Neutral colours (Black, Gray, Silver, White) dominate listings, reflecting a market that prioritizes resale value and practicality over personalization.
- **Caveat**: Findings are based on asking prices from active listings, not completed sales, so they reflect seller/supply-side positioning rather than confirmed transaction prices.

---

## 🎯 Strategic Takeaways

| Audience | Recommendation |
|---|---|
| **Buyers** | Target imported, 2005–2015 vehicles in the Average Use mileage category for the strongest value and negotiating leverage |
| **Dealers** | Toyota is highly saturated; Lexus and Mercedes-Benz offer stronger differentiation opportunities in the mid-premium segment |
| **Investors** | Watch the post-2020 segment — its low liquidity paired with economic pressure could create future repricing opportunities |

---

## 📁 Repository Structure

```
├── data/                   # Raw and cleaned dataset (Cars45 listings)
├── nigeria_car_market.pbix # Power BI dashboard file
├── screenshots/            # Dashboard preview images
└── README.md               # Project documentation
```

---

## 🚀 How to Use

1. Clone this repository
2. Open `nigeria_car_market.pbix` in Power BI Desktop
3. Explore the interactive filters by selling condition, maker, mileage, and year

---

## ⚠️ Research Limitations

This analysis is based on **active listing data**, not completed sales transactions. Figures reflect asking prices and seller-side positioning rather than confirmed realized sale prices. The brand-new category (0.23% of records, ~4 listings) is a small sample and should not be treated as a statistically stable price benchmark.

---

## 👤 Author

**Awe Daniel Olamilekan (Sphere)**
Data Analytics Intern, AnalystLab Africa
[LinkedIn](#) | [GitHub](#)
