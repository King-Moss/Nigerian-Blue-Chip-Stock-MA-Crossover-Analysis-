# 📈 Nigerian Blue-Chip Stock MA Crossover Analysis (2020–2025)

This project applies a **Moving Average Crossover Strategy** to five major Nigerian stocks from 2020 to 2025. The strategy is benchmarked against a **Buy-and-Hold** approach, and performance is evaluated using financial metrics and insightful visualizations.

---

## 🏢 Companies Analyzed
- **Dangote Cement PLC**
- **Seplat Energy PLC**
- **Nestlé Nigeria PLC**
- **Zenith Bank PLC**
- **MTN Nigeria**

---

## 🧠 Strategy Overview

### Moving Averages:
- **MA10** – 10-day Simple Moving Average  
- **MA50** – 50-day Simple Moving Average  

### Trading Logic:
- 📈 **Buy Signal**: When MA10 crosses **above** MA50  
- 📉 **Sell Signal**: When MA10 crosses **below** MA50  

---

## 📊 Performance Analysis

### Visuals Included:
1. **Cumulative Returns** (Strategy vs Buy & Hold)  
2. **Monthly Returns Distribution** (Histograms with KDE)  
3. **Drawdowns Over Time** (Max drops from peaks)  
4. **Performance Metrics Bar Chart**, comparing:
   - ✅ **Sharpe Ratio**
   - 📉 **Max Drawdown**
   - 📊 **Annual Volatility**

Each visualization is professionally styled for clarity and presentation.

---

## 📂 Features
- 📍 Time series plot with price, MA overlays, and buy/sell signals
- 📉 Daily returns and cumulative returns computation
- 🧮 Performance evaluation using Sharpe Ratio, Volatility, and Drawdowns
- 🗃️ Cleaned and formatted stock CSV data
- 🧼 Missing values handled and numeric conversions applied

---

## 🧰 Technologies & Dependencies

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `jupyter` or compatible Python IDE

### Installation
```bash
pip install pandas numpy matplotlib seaborn jupyter

📁 Project Structure
bash
Copy
Edit
Nigerian-Blue-Chip-Stock-MA-Crossover-Analysis/
│
├── Analysis for Dangote Cement PLC.ipynb
├── Analysis for MTN Nigeria.ipynb
├── Analysis for Nestlé Nigeria PLC.ipynb
├── Analysis for Seplat Energy PLC.ipynb
├── Analysis for Zenith Bank PLC.ipynb
├── strategy_performance_analysis.png
└── README.md
🧑‍💼 Author
Moses Udofia
Finance & Data Analysis Enthusiast
📬 Feel free to fork this repo, ⭐ it if you find it useful, and connect for collaboration or discussion!
