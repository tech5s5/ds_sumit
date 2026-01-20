# 📊 Trader Behavior vs Market Sentiment  
### Bitcoin Fear & Greed Index × Hyperliquid Trading Data

**Candidate:** Sumit  
**Role Applied:** Data Science / Machine Learning Engineer  

---

## 🔍 Project Overview

This project analyzes the relationship between **market sentiment (Fear vs Greed)** and **trader behavior on Hyperliquid**, with the goal of uncovering actionable insights that can drive smarter trading strategies in Web3 markets.

By combining Bitcoin market sentiment data with detailed trade-level data, the analysis explores how **profitability, risk-taking, trade direction, and asset selection** vary across different sentiment regimes.

---

## 🎯 Objectives

- Evaluate trader profitability under **Fear vs Greed** market conditions  
- Analyze **risk behavior** using leverage and position sizing  
- Identify **asset-level and directional patterns**  
- Examine whether sentiment-driven effects persist **across time**  
- Translate findings into **practical trading insights**

---

## 📁 Dataset Description

### 1️⃣ Bitcoin Market Sentiment Dataset
- **Columns:** `Date`, `Classification` (Fear / Greed)
- Represents prevailing market psychology

### 2️⃣ Hyperliquid Historical Trader Data
- Trade-level data including:
  - `account`, `Coin`, `side`, `execution price`
  - `size`, `leverage`, `time`
  - `Closed PnL`, `event`, etc.

---

## 📊 Analysis Highlights

Key analyses performed include:
- Overall trade outcome distribution (profit vs loss)
- Top profit- and loss-generating coins
- Coin-level profitability across sentiment regimes
- Directional (Long vs Short) performance analysis
- Asset-specific case studies
- Heatmap analysis of direction × sentiment
- Year-wise profitability trends by sentiment

All insights are supported by visualizations and summarized with concise interpretations.

---

## 📂 Repository Structure


```text
ds_sumit/
├── notebook_1.ipynb          # Main Google Colab notebook          
├── csv_files/                # Processed / intermediate datasets
│   └── *.csv
├── outputs/                  # Saved charts and visualizations
│   └── *.png
├── ds_report.pdf             # Final summarized insights (3–5 pages)
└── README.md                 # Project overview and instructions
---

## 🔗 Google Colab Notebooks

- **Notebook 1:**  
  https://colab.research.google.com/drive/1Fs_jAtp2oud_jwnaAzf77ytcAasGc-W9?usp=sharing  

📌 Access set to **“Anyone with the link → Viewer”**

---

## 📄 Final Report

- **File:** `ds_report.pdf`
- Contains:
  - Problem statement
  - Dataset overview
  - Key findings with visual references
  - Strategy implications
  - Conclusion

---

## ✅ Notes

- All plots are saved under the `/outputs` directory  
- All processed datasets are stored in `/csv_files`  
- The notebook is fully reproducible in Google Colab  

---

## 🚀 Conclusion

This analysis demonstrates that **market sentiment plays a significant role in shaping trader behavior**, influencing not only profitability but also risk exposure and directional bias.  
Understanding these dynamics can provide a meaningful edge in systematic and discretionary trading strategies.

---

**Thank you for reviewing this submission.**
