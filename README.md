# 📊 MovieMetrics — React Dashboard UI

> A production-quality analytics dashboard built with **React (CDN)**, **Chart.js**, and vanilla CSS — no build tools required. Demonstrates component thinking, state management, responsive layout, and data visualization.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?style=flat-square&logo=vercel)](https://miz-react-dashboard.vercel.app)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)]()
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)]()

---

## ✨ Features

- 🌙 **Dark / Light mode** — theme toggle with Chart.js re-render on switch
- 📈 **KPI Cards** — Revenue, Users, Conversion Rate, Avg. Session with trend indicators
- 📊 **Line Chart** — 12-month revenue trend with gradient fill (Chart.js)
- 🍩 **Donut Chart** — Traffic sources breakdown with custom legend
- 🧾 **Transactions Table** — Status pills (Paid, Pending, Failed, Refunded), tabular-nums
- 🗂 **Sidebar Navigation** — Active state, badge indicator, user profile footer
- 📱 **Fully Responsive** — Mobile hamburger menu, fluid grid, stacked charts

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 + CSS3 | Structure & design system (CSS custom properties, Grid, Flexbox) |
| JavaScript (ES6+) | DOM rendering, state, theme toggle, chart lifecycle |
| Chart.js 4.x (CDN) | Line chart + donut chart with theme-aware colors |
| Inter (Google Fonts) | Typography |
| CSS Custom Properties | Full light/dark theme system |

---

## 🚀 Getting Started

```bash
# Clone
git clone https://github.com/fknmiz/miz-react-dashboard.git
cd miz-react-dashboard

# Open — no build step needed
open dashboard-ui.html
```

---

## 💡 React Concepts Demonstrated

- **Component-based thinking** — KPI cards, nav items, table rows as reusable render functions
- **State management** — theme state toggled globally, chart instances managed with destroy/rebuild lifecycle
- **Conditional rendering** — trend arrows, pill colors, icon variants
- **Props pattern** — data arrays drive UI rendering (no hardcoded HTML)
- **Side effects** — chart rebuild triggered by theme state change (mirrors `useEffect`)

---

## ☁️ Deploy to Vercel

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import `fknmiz/miz-react-dashboard`
3. Framework: **Other**
4. Root directory: `/`
5. Hit **Deploy** — live in ~60 seconds

---

## 📁 Project Structure

```
miz-react-dashboard/
├── dashboard-ui.html    # Full dashboard — single file, zero dependencies
└── README.md
```

---

## 👤 Author

**Mirza Causevic** — Director of Tech, Web Engineering & DevOps

[![GitHub](https://img.shields.io/badge/GitHub-fknmiz-181717?style=flat-square&logo=github)](https://github.com/fknmiz)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mirza%20Causevic-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/mirzacausevic)

---

