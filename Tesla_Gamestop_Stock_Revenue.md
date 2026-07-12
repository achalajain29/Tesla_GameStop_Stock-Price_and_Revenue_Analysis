# Stock Revenue Data and Dashboard Visualization

## Project Overview

This project was completed as part of the IBM Data Science Professional Certificate.

The objective of this project is to collect, analyze, and visualize stock market and revenue data for Tesla and GameStop. Historical stock prices were extracted using the yfinance library, while quarterly revenue data was obtained through web scraping techniques. The collected data was then visualized using interactive dashboards to identify trends and patterns in company performance.

---

## Business Problem

Investors often rely on financial data to evaluate a company's performance and growth potential. This project demonstrates how stock prices and revenue data can be combined to gain insights into company performance and market behavior.

---

## Data Sources

### Stock Data
Historical stock price data was extracted using the yfinance Python library.

### Revenue Data
Quarterly revenue data was extracted from HTML tables using web scraping techniques with Requests and BeautifulSoup.

---

## Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **yfinance**
- **Requests**
- **BeautifulSoup**
- **Plotly**
- **Matplotlib**

---

## Data Collection Using yfinance

Historical stock data for Tesla and GameStop was collected using the yfinance library.

The extracted data included:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Trading Volume

The data was stored in Pandas DataFrames for further analysis.

---

## Revenue Data Extraction Using Web Scraping

Quarterly revenue data was collected by scraping financial information from web pages.

The process involved:

- Sending HTTP requests to retrieve webpage content.
- Parsing HTML tables using BeautifulSoup.
- Extracting revenue values and dates.
- Storing the extracted data in structured DataFrames.

---

## Data Cleaning and Preparation

Several preprocessing steps were performed to improve data quality:

- Removed commas and dollar symbols from revenue values.
- Converted revenue data into numeric format.
- Removed missing values.
- Formatted date columns.
- Reset DataFrame indexes.

---

## Dashboard Visualization

Interactive visualizations were created to compare stock prices and company revenues over time.

The dashboards help users:

- Analyze historical stock performance.
- Examine revenue growth trends.
- Identify relationships between revenue and stock prices.
- Compare business performance with market valuation.

---

## Key Findings

### Tesla

- Revenue increased consistently over the years, indicating strong business growth.
- Significant revenue growth was observed after 2019.
- Stock prices rose sharply after 2020, reflecting increasing investor confidence.
- Revenue growth and stock performance showed a strong positive relationship.

### GameStop

* Revenue increased until the mid-2010s and then gradually declined.
* Stock prices remained relatively stable until the dramatic surge in 2021.
* The stock price increase was not supported by similar revenue growth.
* Market sentiment and speculative trading significantly influenced stock performance.

---

## Conclusion

This project demonstrates the use of Python for financial data extraction, web scraping, data cleaning, and dashboard visualization. The analysis revealed that Tesla's long-term stock growth was supported by strong revenue growth, while GameStop experienced significant stock price volatility despite declining revenues. These findings highlight the importance of analyzing both financial fundamentals and market behavior when evaluating investment opportunities.

---

## Project Structure

```text
├── Yfinance_webscraping_practice_project_info.ipynb
├── Web_scraping_project_yfinance.ipynb
├── Tesla_Gamestop_Stock_Revenue.md
├── images/
│   ├── tesla_historical_revenue.png
│   └── Gamestop_revenue_historical_share.png
```
---
## Deliverables Included
* [ Yfinance_webscraping_practice_project_info.ipynb]( Yfinance_webscraping_practice_project_info.ipynb)
* [Web_scraping_project_yfinance.ipynb](Web_scraping_project_yfinance.ipynb)
* [tesla_historical_revenue.png](tesla_historical_revenue.png)
* [Gamestop_revenue_historical_share.png](Gamestop_revenue_historical_share.png)
---

## Author

**Achala Jain**
---
**View My ->**

**[IBM Data Science Professional Certificate-Python Project For DataScience](https://coursera.org/share/309aa1383e69c8e8f637b61adb7eec1b)**

**[Google Data Analytics Professional Certificate](https://coursera.org/share/093874b8b6064ae4741af38e1a44a39f)**
  



