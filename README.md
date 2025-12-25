# 📈 Quantum Trend Matrix

![Pine Script](https://img.shields.io/badge/Pine%20Script-v5-orange.svg)
![TradingView](https://img.shields.io/badge/Platform-TradingView-blue.svg)
![License](https://img.shields.io/badge/License-MPL--2.0-brightgreen.svg)

**Quantum Trend Matrix** is a comprehensive, multi-layered technical analysis indicator for TradingView, designed to provide traders with a versatile tool for analyzing market trends. It fuses several powerful indicators, including a customized Hull Moving Average (HMA), Bollinger Bands (BB), VWAP, and an optional Kahlman Filter, to generate clear, actionable trading signals.

---

### ✨ Key Features

* **📊 All-in-One Trend Analysis:** Combines multiple moving averages, Bollinger Bands, and VWAP into a single, cohesive indicator, reducing chart clutter.
* **🧠 Normalized Hull MA Engine:** Utilizes a custom, smoothed, triple-Hull Moving Average (`hma3`) as its core trend engine, designed to be faster and smoother than traditional MAs.
* **🟢🔴 Clear Visual Signals:** Plots the main trend with color-coded lines (lime for uptrend, red for downtrend) and marks potential entry points with crossover shapes directly on the chart.
* **🌊 Optional Kahlman Filter Smoothing:** Includes an integrated Kahlman filter to further smooth the trend line and reduce market noise for a clearer long-term view.
* **🔔 Built-in Trading Alerts:** Comes with pre-configured alert conditions for "Long" or "Short" crossover signals, so you never miss a potential entry.
* **⚙️ Fully Customizable Inputs:** Allows for complete customization of all parameters, including MA lengths, MA types (EMA, SMA, etc.), sources, BB deviation, and VWAP settings to fit any trading strategy.

---

### 📈 How to Add to TradingView

1.  Open any chart on [TradingView](https://www.tradingview.com/).
2.  Click on the **"Pine Editor"** tab at the bottom of the screen.
3.  Copy the entire content of the `.pine` script file and paste it into the Pine Editor.
4.  Click **"Save"** and give the indicator a name (e.g., "Quantum Trend Matrix").
5.  Click **"Add to Chart"** to see the indicator in action..

---

### ⚙️ Settings Explained

* **`length1` / `length2`:** Controls the calculation period for the moving averages.
* **`MA Type`:** Choose between different moving average types (EMA, SMA, VWMA, WMA).
* **`Source`:** The input source for the MAs (default is `hl2`).
* **`VWAP Length` / `BB Length`:** Sets the lookback period for VWAP and Bollinger Bands.
* **`BB StdDev`:** Sets the standard deviation for the upper and lower Bollinger Bands.
* **`Use Kahlman Filter?`:** A checkbox to enable or disable the Kahlman filter for extra smoothing.

---

### 🔔 Setting Up Alerts

1.  Click the **"Alert"** button (clock icon) in the top toolbar of TradingView.
2.  In the "Condition" dropdown, select **"Quantum Trend Matrix"**.
3.  Choose between **"Long Crossover"** or **"Short Crossover"** conditions.
4.  Configure the rest of your alert settings and click "Create".

---

### 📜 License & Disclaimer

This script is licensed under the Mozilla Public License 2.0. A portion of the code (Moving Average 3.0 script) is licensed under the MIT license by Alex Orekhov (everget).

**Disclaimer:** This tool is for educational purposes only and is not financial advice. Trading carries a high level of risk. The developer is not responsible for any financial losses incurred using this indicator.
