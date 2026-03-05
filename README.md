# 🚲 Bike Sales Analytics Dashboard

> Interactive customer segmentation dashboard — filter, explore, and uncover what drives bike purchases.

**[🔴 Live Demo →](https://pallab-chakraborty.github.io/bike-sales-dashboard/)**

![Bike Sales Analytics Dashboard Preview](https://pallab-chakraborty.github.io/bike-sales-dashboard/preview.png)

---

## 📌 About the Project

This dashboard analyzes **1,000 customer records** to uncover what demographic and behavioral factors predict whether someone buys a bike. Built entirely in a **single HTML file** with zero frameworks — raw Excel data was cleaned, aggregated, and embedded directly into the page.

Every chart, KPI, and table responds instantly to filter changes — letting you drill into segments like *"Single Male customers in North America"* in one click.

| Metric | Value |
|---|---|
| 👥 Total Customers | 1,000 |
| 🚲 Bikes Purchased | 481 |
| 📊 Conversion Rate | 48.1% |
| 💰 Avg Buyer Income | $57,963 |
| 💸 Avg Non-Buyer Income | $54,875 |
| 🌍 Regions Covered | North America, Europe, Pacific |

---

## ✨ Features

- **3-Axis Live Filters** — slice by Gender (Male / Female), Marital Status (Married / Single), and Region (Europe / Pacific / N. America); all charts and KPIs update instantly
- **Average Income by Purchase Decision** — grouped bar showing income gap between buyers and non-buyers, split by gender
- **Purchase by Commute Distance** — line chart revealing the relationship between commute length and bike purchase likelihood (shorter = more likely)
- **Purchase Rate by Age Group** — grouped bars across Adolescent, Middle Age, and Old segments (Middle Age dominates at 383 purchases)
- **Regional Performance Donut** — buyers vs non-buyers broken down across all 3 regions
- **Occupation Breakdown Table** — purchase count and conversion rate per job type (Professionals lead at 67%)
- **Education Level Table** — purchase rates by education (Bachelors top at 72%)
- **4 live KPI cards** that update with every filter: total customers, bikes purchased, avg buyer income, largest market

---

## 🛠️ Tech Stack

| Tool | Role |
|---|---|
| HTML5 + CSS3 | Layout, dark theme, grid animations |
| Vanilla JavaScript (ES6+) | Filter logic, data aggregation, live DOM updates |
| [Chart.js 4.4](https://www.chartjs.org/) | Bar, line, and doughnut charts |
| Google Fonts — Syne + DM Sans | Typography |
| GitHub Pages | Free static hosting |

> **No npm. No bundler. No dependencies beyond a CDN link.** Open `index.html` in any browser — it works instantly.

---

## 📁 Data Source

| File | Rows | Key Columns |
|---|---|---|
| `Raw_Data_Bikes_Sales.xlsx` | 1,000 | ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, Purchased Bike |

Data was cleaned in Excel (removing duplicates, standardizing values, computing Age Brackets via IF formulas), then aggregated and embedded as inline JSON into the HTML.

---

## 💡 Key Insights

- **Income gap is real** — bike buyers earn ~$3,000 more on average than non-buyers across both genders
- **Commute sweet spot** — the 0–1 mile commute range has the highest purchase rate (200 buyers vs 166 non-buyers)
- **Middle Age dominates** — 383 middle-age customers purchased bikes vs only 318 who didn't
- **Pacific converts best** — 113 buyers vs only 79 non-buyers (59% conversion vs 43% in N. America)
- **Education matters** — Bachelors degree holders convert at 72%, nearly double the 29% for Partial High School

---

## 🚀 Run Locally

```bash
git clone https://github.com/pallab-chakraborty/bike-sales-dashboard.git
cd bike-sales-dashboard

# No server needed — just open the file
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 🔗 Related Projects

| Project | Description | Live |
|---|---|---|
| 🛒 Ecommerce Sales Dashboard | 1,500 order lines · revenue, profit, payment & category analysis | [Live Demo](https://pallab-chakraborty.github.io/ecommerce-dashboard/) |
| 🌐 Personal Portfolio | My full developer portfolio | [Visit](https://pallab-chakraborty.github.io/pallab/) |

---

## 👤 Author

**Pallab Chakraborty**
B.Tech CSE · Jawaharlal Nehru University, New Delhi

[![Portfolio](https://img.shields.io/badge/Portfolio-pallab--chakraborty.github.io-blueviolet?style=flat-square)](https://pallab-chakraborty.github.io/pallab/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pallabchakrabortyjnu-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/pallabchakrabortyjnu/)
[![GitHub](https://img.shields.io/badge/GitHub-Pallab--Chakraborty-black?style=flat-square&logo=github)](https://github.com/Pallab-Chakraborty)
[![Email](https://img.shields.io/badge/Email-pallab98__soe@jnu.ac.in-red?style=flat-square&logo=gmail)](mailto:pallab98_soe@jnu.ac.in)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Built with ❤️ & ☕ by <a href="https://pallab-chakraborty.github.io/pallab/">Pallab Chakraborty</a></p>
