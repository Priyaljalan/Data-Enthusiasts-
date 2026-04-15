**Project Update:**

As discussed in class about the integration of different data elements/fields in our project, we have decided just to use the stock price of Alphabet(Google) instead of the three, that is, Microsoft, Apple, and Alphabet (Google). To this, we are adding a new dataset of the US Treasury rates for the last 5 years from 12th March 2021 to 12th March 2026. 

We have sourced our dataset of Alphabet (Google) from the Nasdaq website and the US 10 Year Treasury Yield from the FRED website, and both of the datasets are in CSV format. We have also added these datasets to our GitHub repository. 

Both datasets are publicly available, and the  Alphabet (Google) historical price dataset contains the date, close/last price,	volume, open, high, and low columns, and the treasury rates dataset contains just the date and the treasury yield column. 

Here are our datasets: 

1) Alphabet (Google) - https://github.com/Priyaljalan/Data-Enthusiasts-/blob/main/HistoricalData_GOOGLE.csv
2) US 10 Year Treasury Yield   - https://github.com/Priyaljalan/Data-Enthusiasts-/blob/main/HistoricalData_10YrTreasury.csv

**Timeline:**

Specific Task Updates: 

1. Get historic data on Alphabet (Google) and the US 10 Year Treasury Yield - Completed

2. Clean and organize the datasets - Completed

3. Integrate both datasets - Completed

4. Compute the standard deviation and volatility of the stock - Completed

5. Calculate the percent of daily returns for the stock - Completed

6. Perform the benchmark analysis for the stock - Will be completed by Week 14

7. Calculate the risk-to-reward ratio for the stock - Will be completed by Week 14

8. Calculate Risk premium and correlation - Will be completed by Week 14

9.  Create Visualizations to interpret the results - Will be completed by Week 14

10. Write the final report and review it - Will be completed by Week 15

Above are all the tasks that we need to do after the changes have been made to the project plan. 

**Changes to the Project Plan:**

Based on the feedback received in Milestone 2, we made a significant change to our project.  Initially, the project focused on analyzing and comparing stock performance for three companies: Alphabet Inc., Apple Inc., and Microsoft Corporation with the NASDAQ-100. However, with the help of the feedback, we realized that there was no integration of different data elements or fields taking place in the project. All the datasets extracted by us before had the same set of variables. Therefore, we have refined the scope of our project.  

In our updated project plan, we will be analyzing the stock performance of Apple Inc. in relation to macroeconomic data, specifically the 10 Year Treasury Yield obtained from the FRED database. This will help us understand how a major stock performs in relation to changes in interest rates and a broader financial environment. The 10 Year Treasury Yield is used as a benchmark for long-term interest rates and market expectations. The analysis will extend beyond returns and volatility and include a relationship between stock performance and interest rate movements. 

As part of the updated project plan, we have expanded our analytical framework. In addition to calculating daily return, cumulative return, and volatility, we will now also be focusing on: 

1. Analyzing the correlation between Alphabet Inc. Stock returns and the US 10 Year Treasury Yield 

2. Examining how changes in interest rates impact Apple’s stock performance 

3. Calculating the risk premium to assess whether the return justifies the risk 

Slight changes were introduced to the progress of our project with a change in the scope of the project. Our progress was redirected towards: 

1. Collecting datasets for Alphabet Inc.  

2. Collecting datasets for the US 10 Year Treasury Yield  

3. Cleaning both datasets by standardizing date formats and checking for missing values  

4. Planning the integration process, particularly focusing on aligning time frequencies between datasets 

To conclude, the feedback helped us simplify the scope of the project while strengthening the analytical component. Integrating stock performance with macroeconomic indicators will help us provide deeper insights into the relationship between stock performance, interest rates, and risk-adjusted performance. 

**Challenges:**

**Challenge 1:** One of the main challenges we faced early in the project was finding meaningful data which helped us integrate data with different elements and fields. After our initial decision of using Alphabet Inc., Apple Inc., and Microsoft Corporation along with the NASDAQ-100, we realized that all our datasets contained the same variables which limited the opportunity for cross variable integration.  

**Resolution:** With the help of feedback, we revised the scope of the project and introduced a macroeconomic dataset, the US 10 Year Treasury Yield. This allowed us to integrate stock data with interest rates and improve the analytical scope of the project.  

**Challenge 2:** Another challenge we faced was ensuring proper data cleaning and consistency across datasets. Both datasets were extracted on a daily basis for the date variable. While the frequency issue was avoided with consistent data extraction, we still needed to ensure consistent date formatting, no missing values, and aligned trading days for accurate merging.  

**Resolution:** The date columns for both the datasets followed different formats and this could have caused issues with dataset integration. In order to solve this, we standardized the date format for Alphabet Inc. dataset. This helped us ensure that both datasets followed the same format for date column. We then performed initial dataset analysis on both to check for missing values. We found that the US 10 Year Treasury Yield dataset contained some missing values. We applied forward fill to carry forward the most recent available value to fill in the missing values. This helped us ensure continuity in the date series while preserving as much data as possible for the analysis.  

**Challenge 3:** Another challenge was redefining the analytical approach to the project. Moving to stock macroeconomic analysis required restructuring metrics and objectives.  

**Resolution:** For this, we updated our focus to include daily returns, cumulative returns, volatility for Alphabet Inc., correlation between Alphabet returns and Treasury yields, risk premium, and risk-to-reward ratio analysis.  


**Team Member contributions:**

*Priyal Jalan -* 
 
For reaching this milestone, I sourced the Alphabet (Google) historical stock price data from NASDAQ database. Then cleaned and organized the dataset by looking for any missing values as well as dropping the columns of volume, open, high, and low, as it is not required for our project and analysis. Moreover, I also integrated both datasets using the date column, which also required formatting the date column as both datasets had a different format. Then, I calculated the percent of daily return for the Alphabet (Google) stock price in the last five years, as well as the average of the percent of daily return. Finally, I worked on updating the project timeline as per the feedback we received in class. 

*Naina Shrivastava -* 

For achieving this milestone, I worked on collecting the US 10-Year Treasury Yield dataset from the FRED database. I then assisted with cleaning and organizing the dataset by ensuring consistency in date formats and identifying any inconsistencies in the dataset. I found that the Treasury dataset had some missing values. I applied forward fill to carry forward the most recent available values, as this helped maintain continuity in the time series. I also contributed to refining the scope of the project and updating the analytical framework to include key metrics such as risk premium and correlation. I then worked on computing the standard deviation and volatility for Alphabet Inc. as part of the analysis segment. Finally, I worked on drafting and organizing the status report. 
