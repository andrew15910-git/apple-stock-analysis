# Apple Stock Analysis (AAPL)

This project analyzes the historical performance and risk characteristics of Apple Inc. (AAPL) stock using Python and pandas.

The goal of the project is to demonstrate practical data analysis skills, including data cleaning, return calculation, volatility analysis, drawdown analysis, and time-based aggregation.

---

## 📊 Dataset

- Source: historical daily price data for AAPL
- Columns:
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume

---

## 🔍 Analysis Steps

The notebook includes the following steps:

1. **Data loading and cleaning**
   - CSV parsing
   - Column renaming
   - Date conversion and sorting

2. **Daily returns**
   - Percentage change of closing prices
   - Descriptive statistics of returns

3. **Rolling volatility**
   - 30-day rolling volatility
   - 90-day rolling volatility
   - Visualization of volatility over time

4. **Drawdown analysis**
   - Cumulative maximum price
   - Drawdown calculation
   - Maximum drawdown identification and visualization

5. **Yearly returns**
   - Aggregation of returns by calendar year
   - Bar chart visualization

---

## 📈 Key Insights

- Apple (AAPL) demonstrates a positive long-term return with moderate daily volatility.
- Risk is not constant over time; rolling volatility highlights periods of increased market stress.
- Maximum drawdown shows that even strong assets can experience significant temporary losses.
- Performance varies significantly across years, which is important for reporting and risk communication.

---

## 🛠️ Technologies Used

- Python
- pandas
- matplotlib
- Jupyter Notebook

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

---

## 👤 Author

Andrii Farina  
Junior Data Analyst  

- GitHub: https://github.com/andrew15910-git
- Location: Germany