# Crypto Trader Sentiment Analysis

This project analyzes crypto trading history together with the Fear & Greed Index to understand how market sentiment affects trader profit and loss.

## Files in this project
- `analysis.ipynb` → Jupyter notebook containing full code and analysis  
- `historical_data.csv` → Large dataset of all trading records  
- `fear_greed_index.csv` → Fear & Greed Index data  
- `README.md` → Project explanation

## What the project does
1. Loads trading data and sentiment data  
2. Cleans timestamps and formats dates  
3. Merges both datasets using the `date` column  
4. Calculates:
   - Daily profit & loss  
   - How PnL changes during Fear, Greed, and Extreme Greed  
5. Creates graphs such as:
   - Sentiment vs PnL  
   - Daily PnL trends  

## How to run
1. Open `analysis.ipynb` in Jupyter Notebook  
2. Run all cells  
3. View the graphs and results

## Requirements
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## Author
Kavya  
