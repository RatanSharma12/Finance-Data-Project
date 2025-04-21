# 💹 Finance Data Analysis Project

This project focuses on performing exploratory data analysis (EDA) on stock price data of major U.S. banks from **2006 to 2016**. The goal is to uncover trends, compare volatility, and visualize performance during key financial events like the **2008 financial crisis**.

## 📌 Project Goals
- Fetch stock price data using `pandas-datareader`
- Organize multi-level stock data for analysis
- Calculate daily returns and identify best/worst performing days
- Visualize volatility and trends using various plots
- Perform technical analysis using moving averages and Bollinger Bands

## 🏦 Banks Analyzed
- Bank of America (BAC)  
- Citigroup (C)  
- Goldman Sachs (GS)  
- JPMorgan Chase (JPM)  
- Morgan Stanley (MS)  
- Wells Fargo (WFC)

## 📊 Key Features
- Built multi-indexed `DataFrame` for cleaner analysis by ticker and metric
- Used `.pct_change()` to calculate daily return percentages
- Visualized:
  - **Pairplots** of returns to compare risk profiles
  - **Distribution plots** of returns in key years (e.g., 2008, 2015)
  - **Correlation heatmaps and clustermaps** of bank stocks
  - **Rolling averages** and **candlestick charts**
- Identified Citigroup as the most volatile bank stock over the period

## 🛠 Technologies Used
- Python 3.x  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Plotly  
- Cufflinks  
- pandas-datareader

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/finance-project.git
2. Installing: pip install pandas matplotlib seaborn plotly cufflinks pandas-datareader
3. Launch the jupiter notebook: jupyter notebook 03-Finance-Project.ipynb

📬 Contact
Have questions or feedback? Reach out via:
📧 [mr.ratansharma12@gmail.com or GitHub]




