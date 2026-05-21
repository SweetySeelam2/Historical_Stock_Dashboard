# Tesla vs GameStop Stock and Revenue Analysis

## Project Overview
This project analyzes and visualizes historical stock prices and quarterly revenue data for Tesla (TSLA) and GameStop (GME) using Python libraries such as yfinance, pandas, BeautifulSoup, and matplotlib.

The project was completed as part of the IBM Python Project for Data Science course.

---

## Objectives
- Extract historical stock market data using the yfinance API
- Perform web scraping to collect revenue data
- Clean and preprocess financial datasets
- Visualize stock prices and company revenue trends
- Compare Tesla and GameStop financial performance

---

## Technologies Used
- Python
- Jupyter Notebook
- pandas
- yfinance
- BeautifulSoup (bs4)
- requests
- matplotlib

---

## Project Structure

```bash
├── Final_Assignment.ipynb
├── README.md
```

---

## Installation

Install the required libraries before running the notebook:
```
pip install yfinance
pip install bs4
pip install matplotlib
pip install html5lib
pip install lxml
```

### Import Libraries
```
import yfinance as yf
import pandas as pd
import requests
from bs4 import BeautifulSoup
import matplotlib.pyplot as plt
```

---

## Project Tasks
**Question 1: Extract Tesla Stock Data**
- Used yfinance to download Tesla stock data
- Reset dataframe index
- Displayed first five rows

**Question 2: Extract Tesla Revenue Data**
- Used web scraping techniques
- Cleaned revenue column
- Displayed last five rows

**Question 3: Extract GameStop Stock Data**
- Downloaded GameStop stock data using yfinance
- Reset dataframe index
- Displayed first five rows

**Question 4: Extract GameStop Revenue Data**
- Collected GameStop revenue data
- Cleaned and formatted dataset
- Displayed last five rows

**Question 5: Tesla Stock Visualization**
- Created Tesla stock and revenue graphs using matplotlib

**Question 6: GameStop Stock Visualization**
- Created GameStop stock and revenue graphs using matplotlib

---

## Graph Function
```
def make_graph(stock_data, revenue_data, stock):
```

This function visualizes:
- Historical stock prices
- Historical quarterly revenue

---

## Key Insights
- Tesla showed strong long-term growth in both stock price and revenue.
- GameStop experienced significant stock volatility around 2021.
- Revenue trends and stock trends do not always move together.

---

## Results

The project successfully:

- Extracted stock data
- Performed web scraping
- Cleaned financial datasets
- Generated comparative visualizations

---

## Author

Sweety Seelam

---

## License

This project is created for educational purposes as part of the IBM Data Science coursework.
