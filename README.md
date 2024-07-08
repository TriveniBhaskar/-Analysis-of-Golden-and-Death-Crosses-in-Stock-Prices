# Analysis of Golden and Death Crosses in Stock Prices - Cloud Computing
The project delves into analyzing the impact of Golden and Death Crosses on stock prices over a span of five years. Golden Crosses signify bullish trends, occurring when a short-term moving average crosses above a long-term one, while Death Crosses indicate bearish trends, where the short-term average crosses below the long-term one.

**Data Management and Preparation:**
Stock data was initially stored in a Google Cloud Bucket and efficiently imported into a Cloud SQL database. A dedicated table within the stocks-database instance was created for structured and scalable data storage. This setup ensured streamlined data handling and facilitated seamless retrieval for analysis.

**Methodology and Analysis:**
The study employed daily moving averages (DMA) to smooth out price fluctuations and highlight underlying trends. Specifically, a 50-day and a 200-day moving average were calculated for each stock to identify instances of Golden and Death Crosses. Data preprocessing steps included rigorous cleaning, data type conversion, and sorting to maintain data accuracy and integrity throughout the analysis.

**Identification of Crosses and Post-Cross Analysis:**
Golden and Death Crosses were identified based on the movement of these moving averages. The project meticulously tracked post-cross price movements over varying time frames ranging from 1 week to 6 months. The focus was on analyzing the percentage increases following Golden Crosses and decreases after Death Crosses to assess their impact on stock performance.

**Findings and Insights:**
The analysis revealed compelling insights into the predictive nature of Golden and Death Crosses. Golden Crosses consistently preceded significant price increases, supporting their bullish implications. Conversely, Death Crosses were associated with notable price declines, reaffirming their bearish significance. The study also highlighted that the magnitude and duration of these price movements varied, with longer time frames often exhibiting more pronounced effects.

**Challenges and Considerations:**
Despite encountering technical challenges such as processing power and computational efficiency, the project successfully provided actionable insights for trading strategies. It recommended longer holds following Golden Crosses to capitalize on potential uptrends, while advising caution and risk management strategies post-Death Crosses to mitigate losses.

**Conclusion:**
In conclusion, the analysis underscored the predictive power of Golden and Death Crosses in guiding trading decisions. By leveraging historical stock price data and DMA techniques, the project offered valuable insights that traders and investors can use to refine their investment strategies and optimize portfolio performance based on market trends and risk preferences.
