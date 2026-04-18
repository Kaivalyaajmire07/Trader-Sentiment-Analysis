# 📊 Trader Performance vs Market Sentiment Analysis

## 🔹 Overview

This project analyzes how market sentiment (Fear vs Greed) impacts trader behavior and performance. The goal is to derive meaningful insights and actionable trading strategies using real trading data.

---

## 🔹 Dataset

* Bitcoin Market Sentiment (Fear/Greed Index)
* Historical Trader Data

---

## 🔹 Methodology

* Data cleaning and preprocessing
* Timestamp conversion and alignment at daily level
* Merging datasets using date
* Feature engineering:

  * Average PnL
  * Win Rate
  * Trade Count
  * Average Trade Size
* Sentiment-based analysis
* Trader segmentation and clustering (bonus)
* Predictive modeling (bonus)
* Interactive Streamlit dashboard (bonus)

---

## 🔹 Key Insights

* Traders achieve higher profitability during Fear periods
* Trading activity is significantly higher during Fear
* Larger trades during Greed do not guarantee better returns

---

## 🔹 Strategy Recommendations

* Increase trading activity during Fear periods to leverage volatility
* Reduce position sizes during Greed periods to minimize risk

---

## 🔹 Project Structure

```
.
├── Trader_Sentiment_Analysis.ipynb
├── app.py
├── final_metrics_data.csv
├── README.md
```

---

## 🔹 How to Run

### ▶️ Run Notebook

Open the `.ipynb` file in Jupyter Notebook or Google Colab and execute all cells.

### ▶️ Run Dashboard

```bash
streamlit run app.py
```

---

## 🔹 Requirements

Install dependencies using:

```bash
pip install pandas numpy matplotlib scikit-learn streamlit
```

---

## 🔹 Conclusion

This project demonstrates that market sentiment plays a crucial role in trader performance and behavior. Adapting strategies based on sentiment can significantly improve trading outcomes.

---

## 🔹 Author

Kaivalya Ajmire
Data Science & Machine Learning Enthusiast
