# Cryptocurrency Dashboard- Power BI

![image](https://github.com/user-attachments/assets/bcd84316-02c6-43cd-b42c-51b0123c79f8)




## Project Overview

This project focuses on creating an interactive cryptocurrency dashboard in Power BI using data sourced from Kaggle. The main goal is to visualize key cryptocurrency metrics, perform predictive analysis, and implement custom visualizations with design elements such as neon effects. The dataset includes popular cryptocurrencies like Bitcoin, Dogecoin, and Ethereum, and the dashboard is designed to provide a comprehensive view of the market over time.

## Cryptocurrency Dashboard Image -

![CryptoCurrency Dashboard Image- Power BI](https://github.com/user-attachments/assets/7d86045c-c754-4cca-95c2-f92c6b351704)

![CryptoCurrency Dashboard Image- Power BI2](https://github.com/user-attachments/assets/cca71754-ae09-4654-894f-cd72fe5bb0d4)




## Steps Covered
### Data Preparation: Clustering CSV Files into One Table Using Excel
**Data Source:** The cryptocurrency dataset was downloaded from Kaggle. It contains historical data on various cryptocurrencies such as Bitcoin, Dogecoin, and Ethereum, with attributes like date, price, market capitalization, and volume.

**Data Cleaning and Clustering:**
- Multiple CSV files from Kaggle were consolidated into a single table using Excel. This was done by merging the files based on the "date" column to align the data across different cryptocurrencies.
- Unnecessary columns were removed, and missing values were handled by either replacing them with averages or removing irrelevant records.
- The final table included key metrics such as date, open price, close price, high price, low price, volume, and market cap for each cryptocurrency.

### 2. Neon Effect in Power BI Dashboard Visuals
**Design Philosophy:** To make the dashboard visually appealing and distinguish it from traditional corporate dashboards, neon effects were applied to key visuals like cards and line charts.

**Implementation:**
- In Power BI, the visuals (cards, bar charts, line charts) were customized by modifying background colors and adding border effects that mimic a neon glow.
- Bright, saturated colors were selected (pinks, greens, yellows) to create a futuristic feel, especially for highlighting metrics like the highest price, sum of volume, and market capitalization.
- Custom fonts were used to enhance the visual aesthetics and create a vibrant, eye-catching dashboard.

### 3. Forecasting/Prediction in Power BI
**Predictive Analysis:** Using Power BI’s built-in forecasting tools, a prediction model was applied to the historical price data of Bitcoin.
- A line chart was created showing the historical trend of the Bitcoin market cap from 2013 to 2021, and Power BI’s forecasting feature was used to predict potential future trends.
- The forecast settings were customized to extend the data into 2022, using a confidence interval to provide users with an understanding of potential price fluctuations.
- The forecast helps visualize projected market movements based on past data trends, giving an indication of where prices and market capitalization might head in the future.

### 4. Cryptocurrency Dataset Used

**The dataset consisted of multiple cryptocurrencies including:**

**Bitcoin:** The pioneer in the cryptocurrency space with extensive historical data dating back to 2013.

**Dogecoin:** A popular meme-based cryptocurrency with volatile price movements.

**Ethereum:** One of the leading blockchain platforms, widely known for smart contracts and decentralized applications.

**Data Overview:**

- Bitcoin had the highest market capitalization in the dataset, making it a key focus of the dashboard.
- Ethereum showed consistent growth in its market cap and volume, alongside Dogecoin's more sporadic spikes.
- Key metrics visualized include the sum of volume, maximum high, minimum low, and average market cap.

**5. Multiple Page Power BI Report**

**The report spans multiple pages to provide a detailed analysis of various aspects of cryptocurrency:**

**Overview Page:** 
- Displays overall market trends, with summary cards for key metrics such as total volume (59T), highest price ($64.9K), and total market capitalization ($513T).
- Yearly Trends Page: Focused on the evolution of the market year by year, highlighting the dramatic growth in market cap and price across the years from 2013 to 2021.
- Cryptocurrency Specific Pages: Separate pages were created for each cryptocurrency (Bitcoin, Ethereum, Dogecoin), where detailed metrics like high, low, open, close, volume, and price fluctuations are displayed.

**6. Interconnected Multiple Page Dashboard**

**Interactivity:** The Power BI dashboard is fully interactive, with slicers and filters allowing users to navigate between pages and focus on different time frames and cryptocurrencies.
- A slicer was added to filter by year, enabling users to explore how the market has changed over time.
- The visuals across all pages are interconnected, allowing for seamless cross-filtering. For example, selecting a specific year on the Yearly Trends page updates the corresponding charts on cryptocurrency-specific pages.
- Drill Through: Users can right-click on summary visuals and drill through to more detailed views on specific cryptocurrencies or metrics.
- Navigation: Custom navigation buttons were created for ease of movement between pages.
 
## Technical Insights and Statistical Analysis-
  
**Volume Analysis:** The total volume for all cryptocurrencies over the dataset's time span was 59T. This metric highlights the scale of trading activity and liquidity within the market.

**Price Analysis:** Bitcoin’s maximum high was recorded at $64.9K, while the dataset included a $0 minimum for other smaller or less traded cryptocurrencies.

**Market Capitalization:** The total market cap across all cryptocurrencies was $513T, showing the significant size and value the cryptocurrency market holds.

**Forecast Confidence Interval:** The forecasting model was applied with a 95% confidence interval, which indicated a potential range of outcomes for future prices based on historical volatility.

## Conclusion
This Power BI report provides a holistic view of the cryptocurrency market from 2013 to 2021, with predictions for future trends. By utilizing Excel for data consolidation, adding neon visuals for modern aesthetics, and applying Power BI’s forecasting tools, the project effectively analyzes and presents key metrics, offering valuable insights into the volatile world of cryptocurrencies.
