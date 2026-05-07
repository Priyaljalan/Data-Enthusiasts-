# Data-Enthusiasts-

Title: Title of your project

**Contributors:**

1. Priyal Jalan
2. Naina Shrivastava

**Summary:** [500-600 words] Description of your project, motivation, research question(s), and any findings.
This project analyzes the relationship between the stock performance of Alphabet Inc. (Google) and macroeconomic conditions represented by the United States 10-Year Treasury Yield. The main objective is to analyze how fluctuations in long-term interest rates influence the returns, volatility, and risk-adjusted performance of a major technology company over time. The analysis uses historical daily stock price data for Alphabet Inc. along with daily Treasury Yield data from March 12, 2021, to March 12, 2026. 

Research or Business Question(s):

1. What is the correlation between Alphabet Inc. Stock returns and the US 10 Year Treasury Yield?

2. How do changes in interest rates impact Apple’s stock performance?

3. What is the risk premium, and does the return justify the risk?

Here are our datasets:

Alphabet (Google) - https://github.com/Priyaljalan/Data-Enthusiasts-/blob/main/HistoricalData_GOOGLE.csv

US 10 Year Treasury Yield - https://github.com/Priyaljalan/Data-Enthusiasts-/blob/main/HistoricalData_10YrTreasury.csv

**Data profile:** [max 2000 words] For each dataset used, describe its structure, content, and characteristics. Specify the location of the dataset files in your project repository. Discuss any ethical or legal constraints associated with the data, and explain how the datasets relate to your questions

**Data quality:** [500-1000 words] Summary of the quality assessment.

**Data cleaning:** [max 1000 words] Summarize the data cleaning operations you performed and explain how each operation addressed specific data quality issues in your datasets.

**Findings:** [~500 words] Description of any findings including numeric results and/or visualizations.

**Future work:** [~500-1000 words] Brief discussion of any lessons learned and potential future work.

**Challenges:**

Challenge 1: One of the main challenges we faced early in the project was finding meaningful data, which helped us integrate data with different elements and fields. After our initial decision to use Alphabet Inc., Apple Inc., and Microsoft Corporation, along with the NASDAQ-100, we realized that all our datasets contained the same variables, which limited opportunities for cross-variable integration.

Resolution: With feedback, we revised the project scope and introduced a macroeconomic dataset: the US 10 Year Treasury Yield. This allowed us to integrate stock data with interest rates and improve the analytical scope of the project.

Challenge 2: Another challenge we faced was ensuring proper data cleaning and consistency across datasets. Both datasets were extracted on a daily basis for the date variable. While the frequency issue was avoided with consistent data extraction, we still needed to ensure consistent date formatting, no missing values, and aligned trading days for accurate merging.

Resolution: The date columns for both datasets followed different formats, and this could have caused issues with dataset integration. In order to solve this, we standardized the date format for the Alphabet Inc. dataset. This helped us ensure that both datasets followed the same format for the date column. We then performed initial dataset analysis on both to check for missing values. We found that the US 10 Year Treasury Yield dataset contained some missing values. We applied forward fill to carry forward the most recent available value to fill in the missing values. This helped us ensure continuity in the data series while preserving as much data as possible for the analysis.

Challenge 3: Another challenge was redefining the analytical approach to the project. Moving to stock macroeconomic analysis required restructuring metrics and objectives.

Resolution: For this, we updated our focus to include daily returns, cumulative returns, volatility for Alphabet Inc., correlation between Alphabet returns and Treasury yields, risk premium, and risk-to-reward ratio analysis.

**Reproducing:** Sequence of steps required for someone else to reproduce your results.

**References:**

1. Alphabet(Google) Stock Price dataset: https://www.nasdaq.com/market-activity/stocks/goog/historical?page=1&rows_per_page=10&timeline=y5
2. US 10 Year Treasury Yield dataset: 
