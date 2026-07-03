# 🏔️ YatraYatri — Business Investment Planner

> **A smart, interactive financial planning tool for trek tourism entrepreneurs.**  
> Built for [YatraYatri](https://www.instagram.com/yatrayatri.in/) — a travel guide business offering curated group & solo treks across the Himalayas.

🔗 **Live Demo:** [aastha381.github.io/yatrayatri-planner](https://aastha381.github.io/yatrayatri-planner/)

---

## 📌 Problem Statement

Starting a trek tourism business involves dozens of financial decisions — how to split your capital, how many people to hire, when you'll break even, and how to survive the off-season. This planner solves all of that in one place.

> *"I have money to invest in my business but don't know how to invest it — what factors to consider, how to take care of finances, how many people to hire."*

---

## ✨ Features

### 💰 Live Investment Calculator
- Enter any capital amount (₹1L to ₹50L) — **every value on the page updates instantly**
- Quick preset buttons: ₹1L, ₹2.5L, ₹5L, ₹10L, ₹20L, ₹50L

### 💯 Business Readiness Score
- Dynamic 0–100 health score that updates as you adjust any input
- Color-coded grade: Excellent / Good / Fair / Needs Work
- Tip chips that highlight what's dragging your score down

### 🚨 Live Smart Alerts Panel
- Real-time contextual alerts based on your actual numbers
- **Red errors** — Emergency fund too low, HR runway critical, Legal underfunded
- **Yellow warnings** — Thin margin, slow break-even, under-allocated budget
- **Green successes** — Great margin, stable HR runway, fast recovery

### 🎯 7-Category Investment Allocation with Sliders
Each category has a draggable slider with live ₹ breakdown:

| Category | What it Covers |
|---|---|
| 🚌 Operations & Logistics | Transport, stay, camping gear, safety equipment, kitchen |
| 📣 Marketing & Branding | Instagram/Google Ads, photography, influencers, content tools |
| 👥 Human Resources | 3-month salary buffer for all staff |
| ⚖️ Legal & Compliance | Business registration, GST, travel agent license, insurance |
| 💻 Technology | Website, booking system, CRM, accounting software |
| 🎓 Training & Certifications | WFR, IMF/NIMAS guide certs, altitude training |
| 🆘 Emergency Fund | Medical evacuation, weather delays, refunds, off-season survival |

### 👥 Staff & Salary Planner
- Fully editable **headcount AND salary per person** for every role
- Roles: Trek Guide, Marketing Executive, Finance Person, Customer Support, Cook, Porter
- Auto-calculates monthly payroll, annual cost, and HR budget runway
- Warns if salary buffer covers less than 3 months

### ⚡ Trek Quick-Fill (Break-Even)
- Click **🏔 Panch Kedar**, **🛕 Char Dham**, or **⛺ Kuari Pass** to instantly pre-fill realistic package price, group size, and variable costs
- All break-even projections update automatically

### 📈 Break-Even & Revenue Calculator
- Revenue per trip, variable cost, gross margin
- Monthly revenue and net profit
- Number of trips and months needed to recover full investment
- Financial runway (months you can survive with zero revenue)

### 📅 12-Month Cashflow Projection
- **Bar + line chart** — Revenue vs Total Cost per month, with Cumulative P&L line
- **Seasonality toggle** — applies real Himalayan season multipliers (monsoon Jul–Aug dip, winter Nov–Feb dip)
- **Month-by-month table** — trips, revenue, variable cost, fixed cost, net profit, cumulative P&L
- **Orange highlighted row** = the month you recover your full investment

### 🍽️ Food Cost Reference
Detailed per-meal cost breakdown (Breakfast + Lunch + Snacks + Dinner = ₹440/person/day recommended)

### 💡 8 Smart Recommendation Cards
Dynamically highlighted based on your numbers:
- Phase 1 Foundation roadmap
- Marketing strategy (Instagram, Meta Ads, Thrillophilia)
- Hiring strategy (lean start guide)
- Legal must-haves (waiver, insurance, permits)
- Risk factors (monsoon, medical emergency, cancellations)
- Financial best practices
- 0–18 month growth roadmap
- Food experience USP strategy

---

## 🗺️ Current Trek Portfolio

| Trek | Duration | Price Range | Group Size | Season |
|---|---|---|---|---|
| 🏔 Panch Kedar | 12–16 days | ₹25,000–₹50,000/person | 8–15 | May–Jun, Sep–Oct |
| 🛕 Char Dham Yatra | 10–14 days | ₹30,000–₹60,000/person | 10–20 | May–Jun, Sep–Oct |
| ⛺ Kuari Pass | 5–7 days | ₹10,000–₹20,000/person | 8–12 | Apr–Jun, Sep–Nov |

---

## 🛠️ Tech Stack

- **HTML5** — Single-file, no build step needed
- **CSS3** — Custom dark theme with CSS variables, responsive grid, animations
- **JavaScript (Vanilla)** — All calculations, dynamic rendering, chart updates
- **[Chart.js v4](https://www.chartjs.org/)** — Donut allocation chart + 12-month bar/line combo chart
- **[Google Fonts — Poppins](https://fonts.google.com/specimen/Poppins)** — Typography

No frameworks, no dependencies to install. Just open the HTML file.

---

## 🚀 Getting Started

### Option 1 — View Live
Visit: **[aastha381.github.io/yatrayatri-planner](https://aastha381.github.io/yatrayatri-planner/)**

### Option 2 — Run Locally
```bash
git clone https://github.com/AASTHA381/yatrayatri-planner.git
cd yatrayatri-planner
open index.html   # macOS
# or just double-click index.html in any browser
```

---

## 📖 How to Use

1. **Enter your total capital** at the top — all values update across the entire page
2. **Drag the sliders** to adjust how much goes into each investment category
3. **Set your staff headcount and salary** for each role in the Staff Planner
4. **Click a trek button** (Panch Kedar / Char Dham / Kuari Pass) to auto-fill the Break-Even calculator
5. **Toggle seasonality** on the 12-month projection to see realistic cashflow with Himalayan weather patterns
6. **Watch the Health Score and Alerts** update in real time as you make changes
7. **Print / Save PDF** using the button in the top right

---

## 📁 Project Structure

```
yatrayatri-planner/
└── index.html          # Complete self-contained app (HTML + CSS + JS)
```

---

## 📸 About YatraYatri

YatraYatri (यात्रा यात्री) is a Himalayan trek tourism business offering fully guided group and solo treks. Every package includes:
- ✅ All bookings handled end-to-end
- ✅ All-inclusive food: Breakfast + Lunch + Snacks + Dinner
- ✅ Stay arrangements at every stop
- ✅ Transport to & from the trek

📸 Instagram: [@yatrayatri.in](https://www.instagram.com/yatrayatri.in/)

---

## ⚠️ Disclaimer

All figures are **indicative estimates** for planning purposes only. Consult a Chartered Accountant for precise financial planning and legal/tax advice.

---

*Built with ❤️ for smart trek entrepreneurs*
