# 📊 Trader Behavior vs Bitcoin Market Sentiment

This project analyzes the relationship between Bitcoin market sentiment (Fear/Greed) and trader performance using real historical trade data. It was completed as part of the hiring process for the Junior Data Scientist position at Bajarangs/PrimeTrade.ai.

---

## 📁 Datasets

### 1. `historical_data.csv`
- Individual trades: PnL, leverage, position size, time, etc.

### 2. `fear_greed_index.csv`
- Bitcoin market sentiment index
- Columns: `date`, `value` (0–100), `classification` (Fear/Greed labels)

---

## 🎯 Objective

To determine how market sentiment (Fear, Greed, etc.) affects:
- Trader win rates
- Profitability (PnL)
- Trade sizes
- Execution behavior

---

## 🧠 Key Steps

1. **Data Cleaning**: Timestamp parsing, column selection
2. **Feature Engineering**:
   - Win rate = % of profitable trades
   - Aggregated metrics by sentiment
3. **Merging Datasets** on Date
4. **Visualizations** using Seaborn & Matplotlib

---

## 📈 Key Insights

- 📈 **Extreme Greed** results in the **highest PnL and Win Rate**
- 😟 **Fear** and **Extreme Fear** show lowest profitability
- 💰 Larger trades happen even in fearful markets (possibly due to volatility)
- 🧠 Traders can improve performance by aligning strategies with market sentiment

---

## 📊 Visuals

| Metric               | Insight                                      |
|----------------------|----------------------------------------------|
| Win Rate             | ↑ during Greed, ↓ during Fear               |
| Avg PnL              | Highest in Extreme Greed                    |
| Avg Trade Size (USD) | Larger even during Extreme Fear             |

---

## 🛠 Tools Used

- Python 3.10
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 🔗 How to Run

1. Clone the repo or open in Colab
2. Ensure `historical_data.csv` and `fear_greed_index.csv` are in the same folder
3. Run the notebook `Trader_Sentiment_Analysis.ipynb`

---

## 👨‍💻 Author

**Smit Swapnil Patel**  
Junior Data Scientist Candidate  
📧 smitsmit587@gmail.comm 
🔗 www.linkedin.com/in/smit2509 | 🌐 https://github.com/Smit250904/

---

