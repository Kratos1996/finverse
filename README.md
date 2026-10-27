# Finverse · Smart Money Calculators 💸✨

> **Money maths, made magical.**  
> A sleek, ultra-responsive financial calculation suite with interactive real-time visualizations, glassmorphic aesthetics, and client-side mathematics.

---

## 🌟 Overview

**Finverse** is a modern, single-page web application featuring seven financial calculators designed for investors, savers, borrowers, and lenders. Built entirely with vanilla web technologies, Finverse provides instant visual feedback through animated SVG charts, breakdown donuts, and an interactive particle background.

---

## 🧮 Included Calculators

| Calculator | Icon | Description | Key Inputs |
| :--- | :---: | :--- | :--- |
| **SIP** | 📈 | Disciplined monthly investment with compound growth | Monthly amount, Expected return (p.a.), Tenure, Annual step-up % |
| **Lumpsum** | 💎 | Growth projection for one-time capital investments | Total investment, Expected return (p.a.), Time period |
| **Loan EMI** | 🏠 | Equated Monthly Installment for home, car, or personal loans | Principal amount, Interest rate, Loan tenure |
| **Recurring Deposit (RD)** | 🏦 | Term deposits with quarterly compounding interest | Monthly deposit, Interest rate, Tenure |
| **Fixed Deposit (FD)** | 🔒 | Term deposit with customizable compounding intervals | Deposit amount, Interest rate, Tenure, Compounding (Monthly / Quarterly / Yearly) |
| **Lend Money** | 🤝 | Interest and payback calculator for private lending | Principal lent, Annual rate, Duration, Method (Simple vs. Compound) |
| **CAGR** | 🚀 | Compound Annual Growth Rate analysis | Initial value, Final value, Time horizon |

---

## ✨ Features

- **⚡ Real-Time Math**: Calculations update instantly as sliders or numeric fields change.
- **📊 Interactive Visualizations**:
  - **Dynamic Donut Charts**: Displays breakdown ratios (e.g., Invested Capital vs. Wealth Gain).
  - **SVG Growth Charts & Tooltips**: Interactive timeline charts with hover inspection and tracking guides.
- **🌐 Multi-Currency Support**: Switch on-the-fly between:
  - Indian Rupee (`₹` INR)
  - US Dollar (`$` USD)
  - Euro (`€` EUR)
  - UAE Dirham (`AED` AED)
- **🗣️ Multi-Language Support**: Seamless on-the-fly language switching between **English** and **Hindi (हिन्दी)** with persistent preferences, Hindi localized terms, and Devanagari typography (`Noto Sans Devanagari`).
- **🌓 Theme Support**: Instant dark/light mode toggle with native `prefers-color-scheme` detection.
- **🎨 Modern Glassmorphic Design**:
  - Animated floating gradient blur orbs.
  - Interactive radial spotlight tracking cursor movements across cards.
  - Particle physics canvas mesh connecting nodes to cursor.
- **📱 Fully Responsive**: Optimized for desktop, tablet, and mobile with iOS safe-area inset support.
- **🔒 Privacy First & 100% Offline**: Zero tracking, zero third-party telemetry; all formulas execute purely client-side.

---

## 🛠️ Tech Stack

- **Markup**: Semantic HTML5 with SVG chart rendering
- **Styling**: Vanilla CSS3 (Custom properties, CSS Grid & Flexbox, Glassmorphism, Keyframe animations)
- **Logic**: Vanilla JavaScript (ES6+, Canvas 2D Context, `requestAnimationFrame` counters, `Intl.NumberFormat`)
- **Typography**: [Google Fonts](https://fonts.google.com/) (`Space Grotesk`, `Inter`)

---

## 🚀 Getting Started

No build steps or package installations required!

### Option 1: Direct File Open
Double click `index.html` in your file explorer to open directly in any modern web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local HTTP Server

Using Python:
```bash
# In the project directory
python -m http.server 3000
```
Then visit `http://localhost:3000` in your browser.

Using Node.js (`npx serve`):
```bash
npx serve .
```

---

## 👤 Author

**Ishant Sharma**
- 📞 Phone: [+91-7732993378](tel:+917732993378)
- ✉️ Email: [ishant.sharma1947@gmail.com](mailto:ishant.sharma1947@gmail.com)

---

## ⚖️ Disclaimer

*Calculations and projections provided by Finverse are for illustrative and educational purposes only and do not constitute financial advice. Actual investment yields and loan repayments may vary based on financial institution terms and tax regulations.*
