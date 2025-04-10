# stock-market-powerbi-dashboard

This project aims to provide a stock market analysis of major tech companies using the following [Kaggle dataset](https://www.kaggle.com/datasets/saketk511/2019-2024-us-stock-market-data). 

DAX expressions were used to calculate each companies' daily return, cumulative return, MA200, MA50, monthly retun, sharpe ratio, weekly retun and volume change. Multiple DAX tables were created for ease of filtering and creating visuals.

The screenshots of the individal report pages and the full dashboard can be seen below:
![Page 1](Screenshot%201.png)

Line chart providing a comparison of the daily stock performance of six major tech companies (Amazon, Apple, Google, Meta, Microsoft, Nvidia) across a selected timeframe (Feb 2019 - Oct 2022) to show relative daily gains and losses.

![Page 2](Screenshot%202.png)

Line chart providing a comparison of the overall percentage return for each company per year from 2019 to 2024, enabling a comparison of their long-term investment growth.

![Page 3](Screenshot%203.png)

Line chart providing a comparison of the 200-day (dark blue) and 50-day (light blue) moving averages per company, helping to identify trends and potential buy/sell signals.

![Page 4](Screenshot%204.png)

Line chart tracking the average daily change in trading volume for for each company over the whole period, allowing for a comparison of how their trading activity fluctuates day-to-day.

![Page 5](Screenshot%205.png)

Bar chart showing the Sharpe Ratio for each company, allowing for a direct comparison of their risk-adjusted returns.

Scatter plot showing the average daily return (x-axis) and average volume change (y-axis), illustrating the relationship between these two metrics across the different companies' stocks.

![Page 6](Screenshot%206.png)

Scatter plot displaying each day's trading activity per company, plotting the daily return on the x-axis against the daily volume change on the y-axis, allowing for the visual exploration of any potential relationship or clustering.

![Page 7](Screenshot%207.png)

The same scatter plot displaying each day's trading activity with only Amazon selected.

![Page 8](Screenshot%208.png)

Small multiples line chart displaying the average monthly return for each company across each months, allowing for a visual comparison of their monthly performance trends.

![Dashboard](Full%20Dashboard.png)

Full dashboard merging each of the individual visuals, offering a comprehensive overview of the stock market analysis for the major tech companies.

# Repository Overview
This repository contains a [PowerBi file](stockmarket.pbix) used to create the report and dashboard above, screenshots of each report page and a [screenshot of the full dashboard](Full%20Dashboard.png).

