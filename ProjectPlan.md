**Overview:**
  
  This project focuses on analyzing stock performance and volatility of three major technology companies, namely Apple, Alphabet(Google), and Microsoft, along with their relative performance to the NASDAQ-100 index over the last five years. Specifically, the project combines stock performance analyses with volatility and risk analysis. This will help us identify which company provided the highest growth, which stock was the most stable, and if these stocks outperformed the market benchmark. We will also focus on the risk-to-reward ratio to assess the stock’s performance. Finally, we will also determine the average daily return of the three stocks and construct a combined tech portfolio and assess its volatility to the overall market.  
  
  The stock price datasets for Apple, Alphabet, Microsoft, and NASDAQ-100 will be collected and merged using Date as the primary key. This will be in accordance with procedures for data collection, extraction, and schema level integration. The comprehensive dataset will be then checked for quality and cleaned to handle missing values and any inconsistencies. Performance and risk will be assessed by calculating daily returns, overall returns, and volatility metrics and will be visualized using charts and diagrams to highlight growth and stability. To conclude, the project will also record workflow, metadata, and data provenance to guarantee data reproducibility.  
  
  Integrating performance, volatility, and portfolio analysis, this project demonstrates practical application of data integration, cleaning, analysis, and visualization while providing strong insights into growth, risk, and stability into three major technology companies and their performance as compared to the overall market.  

**Team:**

Member 1: Priyal Jalan

Responsibilities:

1. Get historic data on Alphabet (Google) and NASDAQ-100 (Week 4)
2. Clean and organize the datasets (Weeks 11 & 12)
3. Compute the standard deviation and volatility of each stock (Week 13)
4. Compare the standard deviation and volatility of each stock
5. Create Visualizations to interpret the results (Week 13)
6. Write the final report and review it (Weeks 14 & 15)

Member 2: Naina Shrivastava

Responsibilities: 

1. Get historic data on Apple and Microsoft (Week 4)
2. Calculate the percent of daily returns for each stock (Week 13)
3. Perform the benchmark analysis for each stock
4. Calculate the risk-to-reward ratio for each stock (Week 13)
5. Create Visualizations to interpret the results (Week 13)
6. Write the final report and review it (Weeks 14 & 15)

**Research or Business Question(s):**

1. Which of the three stocks performed the best in the past 5 years, and which stocks outperformed the NASDAQ-100?
2. How volatile are these stocks, and how does their volatility compare to their performance against the market benchmark?
3. What is the risk-to-reward ratio for each stock?

**Datasets:**

Historical daily stock price from 12th March 2021 to 12th March 2026 for:: 

1. Alphabet(Google): https://www.nasdaq.com/market-activity/stocks/goog/historical?page=1&rows_per_page=10&timeline=y5 

2. Apple: https://www.nasdaq.com/market-activity/stocks/aapl/historical?page=1&rows_per_page=10&timeline=y5 

3. Microsoft: https://www.nasdaq.com/market-activity/stocks/msft/historical?page=1&rows_per_page=10&timeline=y5 

4. NASDAQ: https://www.nasdaq.com/market-activity/index/ndx/historical?page=1&rows_per_page=10&timeline=y5 


**Timeline:**

  Work on the project will commence in Week 8, with a target of completing it by Week 14. First, we will focus on gathering datasets and setting up the GitHub Repository for this project. Priyal will organize the datasets for Alphabet(Google) and NASDAQ, while Naina will do the same for Apple and Microsoft datasets [Data Collection & Acquisition]. This will be done while ensuring that ethical considerations are followed, including proper utilization of financial datasets, licensing compliance, and citing resources [Data Ethics, Laws, and Governance]. Relevant columns for the project such as Date and Closing Price will be extracted and renamed for consistency across the datasets and to facilitate merging [Data Integration/Schema-level Integration].  
  
  In Week 9, both members will merge the four datasets by Date to create a unified dataset for further analysis. This process will also include cleaning the dataset and handling any missing values and inconsistencies by Priyal [Data Quality and Data Cleaning Methods]. An additional column will be added to represent a simulated portfolio containing the average daily closing price of the three company stocks. Week 10 will focus on calculations [Workflow Automation]. Priyal will compute the standard deviation and volatility of each of the three stocks as well as the newly curated portfolio. She will then compare them to determine which stock is the most stable. They will also be compared with the standard deviation and volatility of NASDAQ to understand whether any of the stocks outperformed the overall market. Meanwhile, Naina will be assessing growth by calculating daily returns and cumulative returns for each of the three company stocks as well as the simulated portfolio. She will then identify the strongest performing stock and conduct benchmark analysis to assess whether any of them outperformed the overall market. The risk to reward ratio will also be calculated to analyze if the investment justifies the level of risk taken by Naina.  
  
  Week 11 will focus on data visualizations and analysis. Both members will develop charts to interpret the results [Workflow Automation]. Weeks 12 and 13 will focus on document workflow, metadata management, and data provenance to ensure reproducibility. These weeks will also include writing, reviewing, and finalizing the project report while integrating all visualizations and insights [Reproducibility and Provenance Metadata and Data Documentation]. Week 14 will focus on any final reviews and necessary changes to be made to the project.  

 
**Constraints:**

  The main constraint in this dataset is the limited data. The dataset only contains stock prices and no information on the reasons that cause the stock price to react in a certain way, such as interest rates, geopolitical factors, economic factors, and company-specific news. This has led to us not knowing what is causing volatility in the stock prices or the changes in stock returns over time. Secondly, company-specific news can really make the stock price very volatile and not impact other company stocks or the market overall, which might lead to the results not being accurate. Moreover, the dataset does not account for any stock splits or dividends that took place, which will affect the returns of the stocks. Finally, the dataset only contains the stock prices for Alphabet (Google), Apple, Microsoft, and NASDAQ-100 for the last 5 years; it will not capture the long-term market cycles. 

**Gaps:**

  There are a few gaps and areas that will need additional input. Although we have the data of the stock prices of the last five years for Alphabet(Google), Apple, Microsoft, and the NASDAQ-100, we will have to see if the dates in all the datasets align with each other so that it does not lead to miscalculation or incorrect comparison and interpretation. Additionally, we still need to think of the most appropriate visualizations that would provide the best interpretation of our results. Finally, there may be additional requirements that might come up as we progress with the course modules, and we will make changes to the project as we progress. 
