# Trader Sentiment Analysis – Data Science Internship Project

**Author:** Kanan  
**Project:** Data Science Assignment (Internship)  
**Tools:** Python, Pandas, Matplotlib, Seaborn, Google Colab

##  Overview
This project analyzes the relationship between **trader behavior** and **market sentiment (Fear/Greed Index)** using real trading data.  
It was submitted as part of a Data Science Internship assignment.

## Folder Contents

ds_kanan/
├── notebook_1.ipynb # Google Colab notebook (main analysis)
├── ds_report.pdf # Final PDF summary report
├── csv_files/
│ └── merged_data.csv # Cleaned & joined dataset
└── outputs/
├── pnl_by_sentiment.png
├── volume_by_sentiment.png
└── avg_pnl_by_coin.png

## Key Analysis

- **Merged** trader execution data with **Fear & Greed Index** by date
- Calculated:
  - Total trade volume by sentiment
  - Profit & loss (PnL) distributions during Fear vs Greed
  - Top coins by average profit
- Created visualizations to reveal patterns in trader behavior

##  Charts Included

-  **Closed PnL by Market Sentiment** (Boxplot)
-  **Trade Volume by Sentiment** (Bar chart)
-  **Average PnL by Coin** (Top 10)

All charts are saved in the `outputs/` folder.

##  Tools & Techniques Used

- Python (Pandas, NumPy)
- Visualization (Seaborn, Matplotlib)
- Google Colab for notebook execution
- Data cleaning & merging
- Exploratory Data Analysis (EDA)
  
##  Notes

- This project uses mock trading data and publicly available sentiment indices.
- Created for internship evaluation purposes.
- No sensitive or confidential data is used.

