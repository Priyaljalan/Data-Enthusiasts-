# Data-Enthusiasts-

**Title: Analyzing the Relationship Between Alphabet Inc.'s Stock Returns and the US 10-Year Treasury Yield from March 12, 2021, to March 12, 2026** 

**Contributors:**

1. Priyal Jalan
2. Naina Shrivastava

**Summary:** 

This project analyzes the relationship between the stock performance of Alphabet Inc. (Google) and macroeconomic conditions represented by the United States 10-Year Treasury Yield. As finance students, the motivation behind this study was to explore the correlation between interest rates and equity market behavior, particularly within the technology sector. The main objective is to analyze how fluctuations in long-term interest rates influence the returns, volatility, and risk-adjusted performance of a major technology company over time. The analysis uses historical daily stock price data for Alphabet Inc. along with daily Treasury Yield data from March 12, 2021, to March 12, 2026.  

Initially, the project focused on analyzing and comparing stock performance for three companies: Alphabet Inc., Apple Inc., and Microsoft Corporation with the NASDAQ-100. Based on the feedback received in Milestone 2 and after reviewing the project scope, we made a significant change to our project. We realized that there was no integration of different data elements or fields taking place in the project. As a result, we decided to analyze the stock performance of Apple Inc. in relation to macroeconomic data, specifically the 10 Year Treasury Yield obtained from the FRED database. This allowed the project to integrate financial market data with economic indicators and develop a stronger analytical framework. 

The project uses two publicly available datasets. The first dataset contains historical stock price data for Alphabet Inc. sourced from the Nasdaq website. The second dataset contains historical US 10-Year Treasury Yield data sourced from the FRED database. Both datasets are stored in CSV format and integrated using the 'date' column. The analysis focuses on identifying how stock returns behave relative to fluctuations in long-term interest rates and whether changes in Treasury yields impact the volatility and risk profile of Alphabet Inc. Throughout the analysis, several financial metrics were computed, including daily returns, cumulative returns, standard deviation, volatility, correlation between stock returns and Treasury yields, risk premium, and risk-to-reward ratio. Visualizations were also generated to better interpret stock price trends, return fluctuations, and the relationship between stock performance and Treasury yield movements over time.

The project additionally emphasizes data quality, reproducibility, and transparency. Cleaning operations such as standardizing date formats, handling missing values using forward fill, removing unnecessary columns, and aligning datasets by trading dates were performed to ensure accurate integration and analysis.The project repository contains all datasets, analysis scripts, visualizations, and supporting documentation required to reproduce the results.

The findings suggest that macroeconomic indicators such as Treasury yields can provide useful context when analyzing stock market performance.Variations in interest rates can influence investor expectations, discount rates, and overall market sentiment, all of which may impact technology companies such as Alphabet Inc..Integrating financial and macroeconomic datasets demonstrates how data integration can improve financial analysis and provide broader insights into market behavior and risk-adjusted performance.

Research or Business Question(s):

1. What is the correlation between Alphabet Inc. Stock returns and the US 10 Year Treasury Yield?

2. How do changes in interest rates impact Alphabet Inc.'s stock performance?

3. What is the risk premium, and does the return justify the risk?

Here are our datasets:

Alphabet (Google) - https://github.com/Priyaljalan/Data-Enthusiasts-/blob/main/HistoricalData_GOOGLE.csv

US 10 Year Treasury Yield - https://github.com/Priyaljalan/Data-Enthusiasts-/blob/main/HistoricalData_10YrTreasury.csv

**Data profile:** [max 2000 words] For each dataset used, describe its structure, content, and characteristics. Specify the location of the dataset files in your project repository. Discuss any ethical or legal constraints associated with the data, and explain how the datasets relate to your questions

The project uses two publicly available financial datasets to analyze the relationship between Alphabet Inc.’s stock performance and the United States 10-Year Treasury Yield. The datasets were particularly selected to combine financial market data with macroeconomic indicators in order to better understand how fluctuations in long-term interest rates may influence stock returns, volatility, and risk-adjusted performance. Both datasets were downloaded in CSV format and stored within the project repository to ensure transparency and reproducibility and contain daily observations spanning from March 12, 2021, to March 12, 2026.

Although both Nasdaq and the FRED database continuously update their information on a daily basis, the datasets used in this project were intentionally limited to observations available through March 12, 2026. This date was selected because it aligned with the beginning of the project analysis and data collection process. Restricting the datasets to a fixed timeframe helped maintain consistency throughout the project and ensured that all calculations, visualizations, and findings were based on a reproducible dataset. 

The repository contains  datasets, analysis notebook, visualizations, scripts, and supporting documentation used throughout the project. Clear and consistent naming conventions were used to improve organization and readability. The repository also contains supporting files such as requirements.txt file which includes softwares used, a data dictionary describing the variables used in the project, and a metadata file in DCAT format.

**Data quality:** [500-1000 words] Summary of the quality assessment.

**Data cleaning:** [max 1000 words] Summarize the data cleaning operations you performed and explain how each operation addressed specific data quality issues in your datasets.

There were a few data cleaning operations performed to improve the quality of the data and ensure accurate integration.


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
