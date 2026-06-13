# 📊 Complete Stock Analyser

A Python-based CLI tool that fetches live stock data and visualises price trends for both Indian (NSE) and global markets.

---

## 🔍 Features

- Fetches **live stock price**, currency, and **day-over-day change %**
- Auto-detects currency — ₹ for NSE stocks, $ for global stocks
- Plots **1 year of daily closing prices** with:
  - 7-day Moving Average
  - 30-day Moving Average
- Supports **Indian NSE stocks** (just add `.NS` to the symbol)
- Interactive **loop-based CLI** — analyse multiple stocks in one session
- Graceful error handling for invalid symbols or network issues

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| yfinance | Live & historical stock data |
| pandas | Data wrangling & moving averages |
| NumPy | Numerical operations |
| Matplotlib | Price trend charts |
| Jupyter Notebook | Development environment |

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install yfinance pandas numpy matplotlib
```

### Run the Analyser

Open the notebook in Jupyter and run all cells, or execute the main script:

```bash
jupyter notebook stock_analyser.ipynb
```

---

## 📈 Usage

```
=========== Complete Stock Analyser =============
Enter the stock symbol (Add '.NS' for Indian Stocks) (or Q to Quit): TCS.NS

==========================
Company name : Tata Consultancy Services Limited
Current price: 3500.0₹
Change : +45.00 (+1.30%)
==========================
```

**Example symbols:**
- Indian stocks: `TCS.NS`, `RELIANCE.NS`, `INFY.NS`
- Global stocks: `AAPL`, `TSLA`, `GOOGL`

---

## 📊 Sample Output

The tool generates a chart like this for every stock:

- **Blue line** — Daily Closing Price  
- **Orange line** — 7-Day Moving Average  
- **Green line** — 30-Day Moving Average  

---

## 📁 Project Structure

```
complete-stock-analyser/
│
├── stock_analyser.ipynb   # Main Jupyter Notebook
└── README.md              # Project documentation
```

---

## 🙋‍♂️ Author

**Arghadeep**  
Aspiring Data Analyst | Python · SQL · Data Visualization  
[LinkedIn](#) · [GitHub](#)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
