# SwingDesk — Indian Stock Swing Trading Dashboard

SwingDesk is a high-performance, responsive single-page dashboard designed specifically for swing trading Indian equities (NSE & BSE). It provides a sleek, minimalist interface featuring curated swing setups, local virtual portfolio tracking, and an analytical workspace, complete with real-time serverless pricing pipelines.

![SwingDesk Preview](https://img.shields.io/badge/UI--Design-Cyberpunk%20Minimalist-00d4aa?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-0097ff?style=for-the-badge)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%2F%20CSS3%20%2F%20JS-f59e0b?style=for-the-badge)

---

## 🚀 Key Features

### 1. Curated Swing Picks
* Dynamic filtering across advanced categories (e.g., *Strong Buy*, *Breakout*, *Bullish News*).
* At-a-glance visualization of core technical flags ($RSI$, $MACD$, $EMAs$, $Volume$, $Bollinger\ Bands$).
* Immediate integration with sentiment indicators and fundamental ratios ($P/E$, $Market\ Cap$, $Sector$).

### 2. Live Serverless Price Engine
* Integrated client-side asynchronous network pipeline drawing live standard market data through an open CORS proxy engine (`allorigins`).
* Automated multi-asset batch scheduler processing state changes every 5 minutes with active counting metrics.

### 3. Virtual Portfolio Tracker
* Local sandbox modeling tools for tracking entry metrics, trailing stops ($SL1$, $SL2$), and target exit points ($T1$, $T2$).
* Live inline structural input fields with reactive calculations mapping global aggregate absolute P&L and percentages ($₹$ and $\%$).

### 4. Optimized Analytics Workspace Matrix
* **Unified Interface:** The inline widget/chart pane has been deprecated to streamline focus on critical multi-timeframe quantitative variables.
* **External TradingView Integration:** Stock cards feature an integrated **Chart Icon ($\\$)** alongside structural metrics. Clicking the icon instantly opens a new tab directed to TradingView, preconfigured with preloaded indicators tailored for swing trading:
  * **Relative Strength Index (RSI)**
  * **Moving Average Convergence Divergence (MACD)**
  * **Simple Moving Average (SMA / EMAs)**
* Fully dynamic workspace allowing you to dynamically add or dismiss asset matrices instantly via local system caches.

---

## 🛠️ Tech Stack & Architecture

* **Frontend Structure:** Standard Semantic HTML5, CSS3 Variable Matrices.
* **Typography & Aesthetics:** Natively rendering Google Fonts (`Syne` & `Space Mono`) wrapped around a modern neon-cyberpunk layout scheme.
* **Data Storage:** Complete browser-level local state persistence via `localStorage`. No database setup required.
* **APIs Used:** Yahoo Finance public chart feeds routed through the AllOrigins proxy platform for zero-auth CORS data mapping.

---

## 📦 Local Installation & Setup

Since SwingDesk is built entirely on a serverless client-side architecture, setup takes less than a minute:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/yourusername/swingdesk.git](https://github.com/yourusername/swingdesk.git)
   cd swingdesk