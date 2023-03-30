# Coffee Trading Trend Analysis

This project is aimed at helping people who are interested in the global coffee production, trading, and consumption. A historical data on the global coffee trade from the International Coffee Organization (ICO)  is retrieved with Pandas. An interactive dashboard is built for highlighting insightful information visually.

## Methods
- Data Visualization: python, Tableuax
- Statistics
- Machine Learning: Regression, Time Series Forcasting, Clustering

### Data Collection

Historical Data on the Global Coffee Trade https://www.ico.org/new_historical.asp 

International Coffee Organization(ICO) provides data on coffee industry over 30 years between 1990-2019. We use 9 .xlsx files: production, domestic consumption, gross opening stocks, exports, imports, re-exports, price to growers, retail price, and consumption recorded for different countries and years.
  
### Data Cleaning

Each excel file should be a feature in the dataframe in pandas. Our goal is to combine the tables in to one, using 'pd.melt'and 'pd.merge'. At the same time, we deal with missing values and redundant values. Also, messy string data is cleaned. 

- Structure: assign proper data type
- Quality: drop empty rows, unified format, remove unnessarily aggregated rows 

### Exploratory Data Analysis

Data Visualization: 

Questions:
1. Countries: The country that becomes the subject of production is predetermined. I would also like to see a distinction between countries that only produce, countries that only consume, and countries that do both.
2.  Production and other features: does production increase if consumption was high in the previous year? Is there a relationship with the previous year's price?
3.  Ratios of domestic/imports/exports by country and continent. How does this relate to other global indices like GDP and population?
4. What's a cause and effect between price and consumption?
5.  What is the relationship between growers and retail prices for both groups? How does this relate to production and consumption?

### Model

1. Regression
2. Time Series Forcasting
3. Clustering of Countries and Years

  
