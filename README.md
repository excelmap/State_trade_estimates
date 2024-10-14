# State_trade_estimates
State Trade Estimates From (2000 – 2022)
Introduction:
The dataset contains 31,671 rows and 6 columns. Here's a summary of the columns:
1.	Commodity: Type of commodity (object/string).
2.	State: The U.S. state associated with the commodity (object/string).
3.	Units: Measurement units, mainly in "Million dollars" (object/string).
4.	Year: The year of the data (integer).
5.	Value: The value of the commodity for that year in million dollars (float).
6.	Unnamed: 5: An empty column with no data, which can be removed.
Next steps for EDA:
1.	Data Cleaning: Remove unnecessary columns and check for missing values.
2.	Summary Statistics: Get an overview of the data distribution.
3.	Visualizations: Create visualizations such as:
o	Time-series plots to show trends over time.
o	Distribution plots for values.
o	Comparison across states or commodities.
Summary of visualization from the dataset:
1.	Time-Series Trend: The first plot shows the average commodity value from 2000 to 2022. There is a general upward trend, suggesting growth in commodity values over time, with some fluctuations.
2.	State Comparison: The second plot highlights the top 10 U.S. states by total commodity value. States like California, Texas, and Iowa have the highest values, indicating their strong contributions to commodity trade.
3.	Commodity Comparison: The third plot displays the top 10 commodities by total value. Some leading commodities, such as soybeans and corn, have much higher total values compared to others.
