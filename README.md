# Data-Enthusiasts-

**Title: Analyzing the Relationship Between Alphabet Inc.'s Stock Returns and the US 10-Year Treasury Yield from March 12, 2021, to March 12, 2026** 

**Contributors:**

Member 1: Priyal Jalan

Responsibilities:

1. Get historic data on Alphabet (Google) 
2. Clean and organize the datasets (Weeks 11 & 12)
3. Integrate both datasets (Week 12)
4. Compute the standard deviation and volatility of the stock (Week 13)
5. Calculate Risk Premium and correlation analysis (Week 14)
6. Analyze the impact of interest-rate changes on Apple Inc. stock performance (Week 14)
7. Create visualizations to interpret the results (Week 14)
8. Write the final report and review it (Weeks 14 & 15)

Member 2: Naina Shrivastava

Responsibilities:

1. Get the historic data on the US 10 Year Treasury Yield (Week 4)
2. Clean and organize the datasets (Weeks 11 & 12)
3. Calculate the percent of daily returns for the stock (Week 13)
4. Perform the benchmark analysis for the stock (Week 14)
5. Calculate the risk-to-reward ratio for the stock (Week 14)
7. Create visualizations to interpret the results (Week 14)
8. Write the final report and review it (Weeks 14 & 15)

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

**Data profile:**

The project uses two publicly available financial datasets to analyze the relationship between Alphabet Inc.’s stock performance and the United States 10-Year Treasury Yield. The datasets were particularly selected to combine financial market data with macroeconomic indicators in order to better understand how fluctuations in long-term interest rates may influence stock returns, volatility, and risk-adjusted performance. Both datasets were downloaded in CSV format and stored within the project repository to ensure transparency and reproducibility, and contain daily observations spanning from March 12, 2021, to March 12, 2026.

Although both Nasdaq and the FRED database continuously update their information on a daily basis, the datasets used in this project were intentionally limited to observations available through March 12, 2026. This date was selected because it aligned with the beginning of the project analysis and data collection process. Restricting the datasets to a fixed timeframe helped maintain consistency throughout the project and ensured that all calculations, visualizations, and findings were based on a reproducible dataset. 

The repository contains  datasets, analysis of the notebook, visualizations, scripts, and supporting documentation used throughout the project. Clear and consistent naming conventions were used to improve organization and readability. The repository also contains supporting files such as the requirements.txt file, which includes software used, a data dictionary describing the variables used in the project, and a metadata file in DCAT format.

Dataset 1: Alphabet Inc. Historical Stock Price Data
The first dataset used in this project contains historical stock price data for Alphabet Inc. (Google). The dataset was obtained from the Nasdaq Historical Data website and downloaded in CSV format. It contains a daily time series of data and includes the company's stock market performance during the selected period for analysis. 
The dataset is stored in the project repository as: HistoricalData_GOOGLE.csv

The dataset contains the following variables:
  1. Date
  2. Close price
  3. Open price
  4. Volume
  5. High
  6. Low
The "Date" column contains the trading day associated with each observation. The “Close Price” column represents the final trading price of Alphabet Inc. for the respective day. These two variables served as the primary variables and are used for return calculations and volatility analysis throughout the project. The remaining variables provide additional information in relation to the daily trading activity. The “Open price” column represents the stock market opening price for the company for the respective date. The “Volume” column indicates the number of shares traded during the trading session. “High” and “Low” columns represent the maximum and minimum trading prices observed during the day.

The dataset contains daily numerical observations that are appropriate for financial analysis, statistical modeling, and visualization. Since the project mainly focused on understanding stock returns and their relationship with Treasury yields, the “Close Price” column became the analytical variable used for the analysis. 

The dataset was used to calculate several financial metrics, such as:
  1. Daily percentage returns
  2. Cumulative returns
  3. Standard deviation
  4. Volatility
  5. Risk premium
  6. Risk-to-reward ratios
These metrics helped understand the company's stock behaviour over time and examine how the stock performed when compared to macroeconomic conditions as represented by the Treasury Yields. During preprocessing and cleaning, variables such as Volume, Open, High, and Low were removed from the dataset because they were not directly required for the final project scope. The project primarily focused on stock return behavior rather than detailed intraday trading activity. This simplification of the dataset helped improve analytical clarity and reduce unnecessary potential holdbacks within the workflow.

The Alphabet Inc. dataset represents structured financial market data with a streamlined structure. As the dataset was sourced from Nasdaq  which is a widely recognized and used financial market data provider, the dataset is considered reliable and appropriate for academic and analytical purposes, hence is appropriate for the project.

Dataset 2: US 10-Year Treasury Yield Data
The second dataset used in this project contains historical United States 10-Year Treasury Yield data. The dataset was obtained from the Federal Reserve Economic Data (FRED) website and downloaded in CSV format. It contains daily observations of the US 10-Year Treasury Yield over the same time period as used for the Alphabet Inc. dataset. 
The dataset is stored in the project repository as: HistoricalData_10YrTreasury.csv

The dataset contains the following variables:
  1. Date
  2. Treasury Yield

The “Date” refers to the observation date associated with each Treasury Yield value. The “Treasury Yield” column represents the interest rate associated with the United States 10-Year Treasury security for that particular date. Since the dataset consists of only these two important variables, there was no requirement to drop any of them for a smoother workflow. The US 10-Year Treasury Yield is commonly used as a benchmark indicator in financial markets because it reflects long-term interest rate expectations, economic outlook, and investor sentiment. Treasury yields can influence discount rates, borrowing costs, and investment decisions, which makes them particularly relevant  when analyzing the performance of growth-oriented technology companies such as Alphabet Inc.. 

The Treasury Yield dataset was integrated with the Alphabet Inc. stock dataset to analyze whether changes in long-term interest rates correlate with changes in stock returns, volatility, and overall performance. Introducing a macroeconomic dataset to the project expanded the analytical scope by introducing variables with different economic interpretations and characteristics. The Treasury Yield dataset contains numerical time series observations and is considered reliable because it is sourced from the FRED database, which is widely recognized and trusted for macroeconomic and financial information. 

Data Collection and Acquisition:
Both datasets used in this project were obtained from publicly accessible online databases. The Alphabet Inc. stock price data was downloaded from the Nasdaq website and  the Treasury Yield dataset was downloaded from the FRED database. The datasets were stored in CSV format to simplify loading, preprocessing, and analysis using Python and Pandas. Python notebook (VS Code) cells and scripts were used to  import datasets into Pandas DataFrames with the pandas.read_csv() function.

The datasets were verified after downloading to ensure successful loading into Pandas DataFrames and maintaining consistency in formatting and structure. Basic data integrity checks were performed by verifying successful file parsing, validating column formatting, ensuring consistency across date fields, and confirming that the datasets loaded correctly without corruption or formatting issues. The datasets are publicly accessible and are small in size, and the project repository directly includes the input CSV files, which are required to reproduce the analysis. This analysis relies on publicly accessible financial and macroeconomic observations. The datasets were used solely for academic purposes and were not modified in any way that could alter the original interpretation or meaning of the data. Proper attribution for both Nasdaq and FRED is included within the References section of the report.

The datasets were selected because they provide a perspective into the financial markets. A key component of the project involved integrating financial market data with macroeconomic data. The two datasets were combined using the “Date” column after standardizing date formats across both datasets. The combined dataset enabled analysis of the relationship between technology stock performance and macroeconomic indicators. Combining these datasets strengthened the project’s analytical framework and improved the ability to generate meaningful financial insights from the analysis.

Storage and Organization:
The project repository was organized to improve transparency, usability, and reproducibility. Easily understandable and self-explanatory file names are used in the repository to allow users to easily understand the purpose of each file and the project workflow. 
The repository includes:
1. Datasets
2. Jupyter notebooks
3. Visualization outputs
4. Documentation files
5. Metadata files
6. Software documentation


**Data quality:** 

A comprehensive data quality assessment was conducted on both datasets before beginning the analysis process. The primary goal of this assessment was to ensure that the datasets were complete, consistent, reliable, and suitable for integration and financial analysis. Since the project involved combining stock market data with macroeconomic data from two different sources, evaluating data quality was necessary to ensure accurate calculations and meaningful analytical results. Python and Pandas were used extensively during the data profiling and assessment process. 

The quality assessment process began with reviewing the structure and formatting of both datasets. Functions such as .dtypes were used to inspect and verify data types, while .value_counts() were used to review the distribution and consistency of observations within important variables. The .isnull() function was used to identify missing values and evaluate dataset completeness prior to preprocessing and integration.

One of the primary issues identified during the quality assessment process involved inconsistencies in the formatting of the Date column between the two datasets. Since the datasets were intended to be integrated using the “Date” column, ensuring consistency in formatting was especially important. We renamed the columns to improve readability and maintain consistency throughout the analysis workflow. Since the datasets were intended to be integrated using the “Date” column, ensuring consistency in formatting was especially important. Another important component of the assessment involved identifying missing values. Although missing values were present within the Treasury Yield dataset, the issue was relatively minor and did not significantly reduce the reliability of the data. The missing observations were identified using .isnull(), documented during the quality assessment stage, and later addressed during preprocessing and cleaning operations. 

Both datasets were also evaluated for duplicate records and structural inconsistencies. After reviewing both datasets, no significant duplication issues were identified. Another important quality consideration involved evaluating consistency in observation frequency and alignment between the two datasets. Although both datasets contained daily observations, financial market data and Treasury Yield data may occasionally differ due to market holidays or reporting schedules. The datasets were therefore carefully assessed to ensure observations aligned correctly following integration.

The Alphabet Inc. stock dataset contained variables such as Open, High, Low, and Volume which were not directly relevant to the final scope of the project. While these variables were not considered quality issues, these columns were dropped in order to simplify the workflow and improve the focus of the project. 

The data quality assessment demonstrated that both datasets were reliable and suitable for financial analysis after preprocessing and cleaning procedures were completed. Identifying issues related to date formatting, missing values, numerical consistency, observation alignment, and structural formatting and addressing them improved the consistency and usability of the integrated dataset and ensured that the project findings were based on accurate and properly aligned financial and macroeconomic data.


**Data cleaning:** 

There were a few data cleaning operations performed to improve the quality of the data and ensure accurate integration. Data cleaning was one of the most important parts because our analysis is dependent on combining two different datasets, historical stock prices for Alphabet Inc. and the US 10-Year Treasury Yield from March 12, 2021, to March 12, 2026. Before performing any analysis, we needed to make sure that both datasets were accurate, consistent, and properly formatted so they could be integrated successfully without any inconsistencies.

The first step that we took in our data cleaning process was to look at both the data sets for any missing values, incorrect data types, and formatting inconsistencies. Although there were no missing values in the Alphabet Inc. stock price dataset, the treasury yield dataset had 55 missing values, and we used forward fill to fill the missing values with the most recent valid Treasury yield forward, as without any values in it could have affected our calculations, such as correlation, volatility, and risk premium analysis. Moreover, the date format of both datasets was different, and so we standardized them into a datetime format, which ensured that while merging the two datasets, we would not face any issues. 

Moving forward, after standardizing formats and handling missing values, both datasets were merged using the Date column. The merged dataset included Date, Closing stock Price,  Treasury Yield, and the return per day of the Alphabet stock price columns. Where the return per day was calculated using the percent change function. 
After the integration of the dataset, we performed additional checks to confirm that the merged dataset did not contain duplicate rows or unexpected missing values, which could be a potential issue for our analysis.

Overall, cleaning the dataset improved the reliability and consistency, reduced missing-data issues, and ensured the dataset was suitable for financial analysis and was based on accurate and well-structured data.

**Findings:** 

The study investigated the connection between changes in the US 10-Year Treasury Yield and stock returns for Alphabet Inc. In order to more effectively understand the connection between stock performance, interest rates, and risk associated, several financial measures and visualizations were produced after the two datasets were cleaned and integrated.

First, we analyzed the average return and volatility of the Alphabet stock price. The average stock price that we got was approximately -0.069. The daily volatility of the stock was calculated using the standard deviation of daily returns, which was approximately 1.92%, and the annual volatility was approximately 30.55%. This indicates that Alphabet stock experienced a relatively high level of price fluctuation during the period we analyzed. Moreover, technology stocks like Alphabet Inc. are generally more sensitive to market expectations and macroeconomic conditions, which might explain the higher volatility observed in the results that we got.

Secondly, we calculated the risk premium and risk-to-reward ratio. The average daily return and annualized return for Alphabet stock were negative during the time period we used. As a result of that, the calculated risk premium we got was approximately -17.39%, which means that the stock underperformed. The risk-to-reward ratio was also negative and was around -1.76, showing that investors were not compensated properly for the level of risk associated with holding the stock. These findings shows us how when the market is uncertain and interest rates are rising, it can reduce the attractiveness of growth-focused technology investments.

The main findings of the project were the correlation between Alphabet’s daily stock returns and changes in Treasury yields. The calculated correlation coefficient was approximately -0.037, indicating a very weak negative relationship between the two variables. This suggests that increases in interest rates were associated with slightly lower Alphabet stock returns, although the relationship between them was not that strong. This shows that higher interest rates can negatively impact growth-oriented technology companies like Alphabet Inc. because future earnings become less important when they are discounted at higher interest rates but the correlation's minor significance level suggests that other elements, like investor attitudes, companies financial results, and overall market conditions, probably had a bigger impact on Alphabet's stock performance during the selected time frame that is 12th March 2021 to 12th March 2026.

Finally, we created several visualizations to support the analysis and interpret the results more effectively. The first two are a line graph showing Alphabet's daily stock price returns, revealing periods of volatility and clear fluctuations in stock performance, and the US 10-Year Treasury Yield, which showed an upward trend in interest rates, although it was not consistent, as there were a few times when it fell. Then, the third was a scatter plot comparing Treasury yield changes with Alphabet stock returns, which showed a weak and widely dispersed relationship, confirming the low correlation between the two. Finally, we made a bar chart comparing the annual return, annual volatility, and risk premium to help summarize the relationship between the return and the investment risk.
Overall, the findings suggest that while interest rates might have some kind of an influence on technology stock performance, the direct relationship between Treasury yield changes and Alphabet stock returns was relatively weak. The analysis points out the significance of merging financial market data with macroeconomic factors to better understand the risk associated with investments and stock market behaviour.

**Future work:** [~500-1000 words] Brief discussion of any lessons learned and potential future work.

**Challenges:**

Challenge 1: One of the main challenges we faced early in the project was finding meaningful data, which helped us integrate data with different elements and fields. After our initial decision to use Alphabet Inc., Apple Inc., and Microsoft Corporation, along with the NASDAQ-100, we realized that all our datasets contained the same variables, which limited opportunities for cross-variable integration.

Resolution: With feedback, we revised the project scope and introduced a macroeconomic dataset: the US 10 Year Treasury Yield. This allowed us to integrate stock data with interest rates and improve the analytical scope of the project.

Challenge 2: Another challenge we faced was ensuring proper data cleaning and consistency across datasets. Both datasets were extracted on a daily basis for the date variable. While the frequency issue was avoided with consistent data extraction, we still needed to ensure consistent date formatting, no missing values, and aligned trading days for accurate merging.

Resolution: The date columns for both datasets followed different formats, and this could have caused issues with dataset integration. In order to solve this, we standardized the date format for the Alphabet Inc. dataset. This helped us ensure that both datasets followed the same format for the date column. We then performed initial dataset analysis on both to check for missing values. We found that the US 10 Year Treasury Yield dataset contained some missing values. We applied forward fill to carry forward the most recent available value to fill in the missing values. This helped us ensure continuity in the data series while preserving as much data as possible for the analysis.

Challenge 3: Another challenge was redefining the analytical approach to the project. Moving to stock macroeconomic analysis required restructuring metrics and objectives.

Resolution: For this, we updated our focus to include daily returns, cumulative returns, volatility for Alphabet Inc., correlation between Alphabet returns and Treasury yields, risk premium, and risk-to-reward ratio analysis.

**Reproducing:** 
To reproduce the results of this project, users should first clone or download the GitHub repository containing all datasets, notebooks, visualizations, metadata files, and supporting documentation containing the details of the analysis. The repository includes all input datasets necessary to reproduce the project findings. 

The repository is organized using clear and descriptive file names to improve readability, usability, and reproducibility.
The repository includes:
  1. Datasets
  2. Jupyter notebooks
  3. Visualization outputs
  4. Documentation files
  5. Metadata files
  6. Python library documentation
     
The primary workflow for the project is contained within the Jupyter notebook: final_project_stock_vs_treasury_analysis.ipynb
The following datasets should be located within the project repository before running the notebook:
  1. Alphabet Inc.: HistoricalData_GOOGLE.csv
  2. US 10 year Treasury Yield: HistoricalData_10YrTreasury.csv

The datasets were sourced from:
  1. Nasdaq Historical Data 
  2. Federal Reserve Economic Data (FRED)
     
The datasets were verified after download by loading both CSV files into Pandas DataFrames using pandas.read_csv(). Data integrity checks included reviewing dataset structure using .dtypes, identifying missing values using .isnull(), checking observation consistency using .value_counts(), and confirming that date columns and numerical variables loaded correctly without formatting or parsing issues.
Users should install the required Python libraries listed in the requirements.txt file to reproduce the analysis,. The project primarily uses the following libraries: 
  pandas
  numpy
  matplotlib

The required packages can be installed using: pip install -r requirements.txt

After installing the dependencies, users should open the Jupyter notebook and run all notebook cells sequentially. The notebook contains all Python code required for:
  1. loading the datasets
  2. assessing data quality
  3. cleaning and preprocessing the data
  4. integrating the datasets
  5. calculating financial metrics
  6. generating visualizations
     
The notebook includes several preprocessing and integration steps. Date columns from both datasets were standardized into a consistent datetime format before integration. Missing values within the Treasury Yield dataset were handled using forward fill methods to maintain continuity in the time-series analysis. The datasets were then merged using the “Date” column to create a single analytical dataset. 
The notebook also calculates several financial metrics including:
  1. Daily percentage returns
  2. Cumulative returns
  3. Standard deviation
  4. Volatility
  5. Correlation between stock returns and Treasury yields
  6. Benchmark analysis
  7. Risk premium
  8. Risk-to-reward ratio
     
In addition, the notebook generates all visualizations used throughout the analysis, including stock trend graphs, Treasury Yield trend visualizations, and comparative plots examining the relationship between Treasury yields and Alphabet Inc. stock returns. 
All scripts, workflow steps, datasets, and visualization outputs required to reproduce the project findings are included within the repository. Supporting documentation files such as the data dictionary, metadata file in DCAT format, README file, and Python library documentation are also included to improve transparency and reproducibility.

The repository additionally contains an MIT License file documenting permissions associated with the original analytical code, visualizations, and documentation created as part of the project.



**References:**

1. Alphabet(Google) Stock Price dataset: https://www.nasdaq.com/market-activity/stocks/goog/historical?page=1&rows_per_page=10&timeline=y5
2. US 10 Year Treasury Yield dataset: 
