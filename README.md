# Miz React Dashboard

Polished React-style dashboard showcase for **KPI storytelling, chart composition, responsive layout, and product-minded frontend craft**.

> **What this repo proves**
>
> Good dashboard UI is not a pile of widgets. It is hierarchy, rhythm, readability, and business context working together on one screen.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-black?style=flat-square&logo=vercel)](https://miz-react-dashboard.vercel.app)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)]()
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)]()

## Features

- **Dark / light mode** with Chart.js re-render on theme switch
- **KPI cards** for revenue, users, conversion rate, and average session depth
- **Line chart** for 12-month revenue trend with gradient fill
- **Donut chart** for traffic-source mix with custom legend
- **Transactions table** with status pills and tabular numeric layout
- **Sidebar navigation** with active state, badge indicator, and profile footer
- **Responsive layout** with fluid grid, mobile menu, and stacked chart behavior

---

## ðŸ›  Tech Stack

| Technology | Usage |
|---|---|
| HTML5 + CSS3 | Structure & design system (CSS custom properties, Grid, Flexbox) |
| JavaScript (ES6+) | DOM rendering, state, theme toggle, chart lifecycle |
| Chart.js 4.x (CDN) | Line chart + donut chart with theme-aware colors |
| Inter (Google Fonts) | Typography |
| CSS Custom Properties | Full light/dark theme system |

---

## ðŸš€ Getting Started

```bash
# Clone
git clone https://github.com/mizcausevic-dev/miz-react-dashboard.git
cd miz-react-dashboard

# Open â€” no build step needed
open dashboard-ui.html
```

---

## ðŸ’¡ React Concepts Demonstrated

- **Component-based thinking** â€” KPI cards, nav items, table rows as reusable render functions
- **State management** â€” theme state toggled globally, chart instances managed with destroy/rebuild lifecycle
- **Conditional rendering** â€” trend arrows, pill colors, icon variants
- **Props pattern** â€” data arrays drive UI rendering (no hardcoded HTML)
- **Side effects** â€” chart rebuild triggered by theme state change (mirrors `useEffect`)

---

## â˜ï¸ Deploy to Vercel

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import `mizcausevic-dev/miz-react-dashboard`
3. Framework: **Other**
4. Root directory: `/`
5. Hit **Deploy** â€” live in ~60 seconds

---

## ðŸ“ Project Structure

```
miz-react-dashboard/
â”œâ”€â”€ dashboard-ui.html    # Full dashboard â€” single file, zero dependencies
â””â”€â”€ README.md
```

---

## ðŸ‘¤ Author

**Mirza Causevic** â€” Director of Tech, Web Engineering & DevOps

[![GitHub](https://img.shields.io/badge/GitHub-mizcausevic--dev-181717?style=flat-square&logo=github)](https://github.com/mizcausevic-dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mirza%20Causevic-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/mirzacausevic)

---
