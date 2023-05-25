# Stock_Metrics_Analyzer

Motivation
The Stock Metrics Analyzer project aims to provide a convenient way to compute various metrics for different stocks listed in the S&P 500 index. By automating the calculation process, this tool simplifies the analysis of key performance indicators and enables users to gain insights into the selected stocks. For simplicity 3 Assests (APPLE INC., AMAZON.COM INC., ALPHABET INC.) are only taken into consideration.

Key Features
Computes a range of metrics, including but not limited to:

1.	Last close price ($)
2.	Operating Margin (%): Average of  operating margins last 4 quarterly reports
3.	EV / (EBITA - Capex): Enterprise value / (EBITDA - Capital Expenditure) [from last annual financial statement]
4.	Stock YTD performance
5.	Revenue - 1 year annualized growth (%) 
6.	Short interest - % of shares shorted in the market on given day

Retrieves up-to-date stock data from reliable sources.
Generates comprehensive reports summarizing the calculated metrics.
Supports the inclusion of additional custom metrics.
It also includes an automatic email sender code which sends the report of the analysis attached as a .csv file to the concerned person.
