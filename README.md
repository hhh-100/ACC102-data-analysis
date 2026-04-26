# AAPL 2024 Stock Performance Analysis

## 1. Problem & User
This project analyzes the full-year stock performance of Apple Inc. (AAPL) in 2024. It aims to help people understand stock price trends, volatility and overall trading behavior based on real academic financial data.

## 2. Data
- **Data Source**: CRSP database, accessed via WRDS platform
- **Date of Access**: [2026-04-26]
- **Time Period**: 2024-01-02 to 2024-12-31
- **Total Data**: 252 daily trading records
- **Key Fields**:
  - date: Trading calendar date
  - BIDLO: Daily lowest price
  - ASKHI: Daily highest price
  - PRC: Daily closing price
  - VOL: Daily trading volume
  - OPENPRC: Daily opening price

## 3. Methods
1. Load and inspect raw CSV dataset with Python pandas
2. Process and standardize date format for time series analysis
3. Calculate financial indicators including daily return and intraday volatility
4. Generate descriptive statistical summary of the dataset
5. Use matplotlib library to plot price trend, volume and return charts

## 4. Key Findings
- AAPL stock showed an overall positive upward trend in 2024
- The average annual closing price was approximately $207
- The highest price reached around $259, while the lowest price was about $165
- Daily trading volume remained stable throughout the whole year
- The stock maintained moderate volatility with no extreme abnormal fluctuations

## 5. How to Run
1. Download all files from this repository
2. Install required libraries using `pip install -r requirements.txt`
3. Open `analysis.ipynb` in Jupyter Notebook
4. Run all code cells sequentially
5. View statistics results and generated visualizations

## 6. Demo Link
[ Paste your project demonstration video link here ]

## 7. Limitations & Next Steps
### Limitations
- Only covers one single stock without market benchmark comparison
- Does not consider external economic or news factors
### Next Steps
- Compare performance with market index and other peer stocks
- Extend the dataset to cover multiple years
- Add basic trend prediction models