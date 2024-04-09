Dataset for Time Series Forecasting


The dataset considers annual data for the period of 1991 to 2024, for 9 of the 19 Eurozone countries, considering these 9 countries have the longest series, thus making it possible to carry out time series analysis. 
The 9 countries are:
Austria, Belgium, France, Germany, Greece, Italy, Netherlands, Portugal, and Spain.
In addition, aggregate values of all the features from the entire eurozone were considered to forecast the exchange rate.
The dataset has 6 features described below, all taken from the OECD (Organization for Economic Cooperation and Development):
1. exr - Annual Purchasing Power Parities and Exchange Rates: This table shows annual Purchasing Power Parities (PPPs) for Gross Domestic Product (GDP), household final consumption expenditure, and actual individual consumption. It also shows exchange rates (annual averages and end of period - I used this one), sourced from the International Monetary Fund's database on International Financial Statistics. Final consumption expenditure is the expenditure of resident households on consumption goods or services. In contrast, individual consumption is the sum of household consumption plus the individual (not collective) consumption of the non-profit institutions serving households (NPISH) and General Government sectors. These indicators were presented in the previous dissemination system in the SNA_TABLE4 dataset. 
Institutional sector: Total economy. 
Counterpart institutional sector: Total economy. 
Financial instruments and non-financial assets: Currency. 
Unit of measure: National currency per US dollar.


2. w - Average annual wages: This dataset contains data on average annual wages per employee in full-time equivalent units in the total economy. Average annual wages per full-time equivalent dependent employee are obtained by dividing the national-accounts-based total wage bill by the average number of employees in the total economy, which is then converted into the full-time equivalent unit by applying the ratio of average usual weekly hours per full-time employee to that of all employees. 


3. Inv - Annual investment by asset and institutional sector: This table shows annual investment (Gross Fixed Capital Formation or GFCF) in dwellings, other buildings, and other structures. The investment in these fixed assets is presented for each institutional sector: Non-financial Corporations, Financial corporations, General Government, Households, and Non-profit institutions serving households (NPISHs). The default presentation is on a country-by-country basis. Users can change the country selected using the ‘Reference area’ filter; or compare a fixed asset (using the ‘Financial instruments and non-financial assets’ filter) for combinations of sectors, countries, and time periods. 
Counterpart institutional sector: Total economy. 
Accounting entry: Expenditure
Transaction: Gross fixed capital formation. 
Unit of measure: National currency. 
Valuation: Standard valuation based on SNA/ESA.


4. Unp - Annual unemployment rates: The infra-annual dataflow on the monthly unemployment rate is a subset of the infra-annual labor statistics database, which contains predominantly monthly and quarterly statistics on the unemployed population by age groups (15+, 15-24, 25-54, 55-64, 15-64 and 15-74 where available - I used all age groups combined) and sex and associated statistical methodological information and associated statistical methodological information, for the OECD member countries and selected other economies. The unemployment rate is calculated as the number of unemployed persons as a percentage of the labor force (i.e., the unemployed plus those in employment). The unemployed are persons in their working age who, in the reference period, do not have a job; are available for work; and, have taken specific steps to find a job. The infra-annual labor statistics compiled for all OECD member countries are drawn from Labour Force Surveys based on the definition provided by the 19th Conference of Labour Statisticians in 2013. The uniform application of these definitions across all OECD member countries results in internationally comparable estimates. 
Measure: Monthly unemployment rate. 
Unit of measure: Percentage of labor force from all groups.


5. prod - Productivity levels: The OECD Productivity Database aims to provide users with the most comprehensive and latest productivity estimates. The update cycle is on a rolling basis: each variable in the dataset is made publicly available as soon as it is updated in the source databases. The productivity database contains data on labor productivity both measured using employment or hours worked and the components of capital and labor inputs. The productivity database in levels, growth rates, and industry contains annual data, while the database on productivity and unit labor costs are quarterly estimates.
Frequency of observation: Annual. 
Combined measure: GDP per hour worked. 
Combined unit of measure: US dollars per hour, exchange rate converted, Current prices.


6. hp - Analytical house prices indicators: Residential Property price indices (RPPIs) – also named House price indices (HPIs), are index numbers that measure the prices of residential properties over time. RPPIs are key statistics not only for citizens and households across the world but also for economic and monetary policymakers. They can help, for example, to monitor potential macroeconomic imbalances and the risk exposure of the household and financial sectors. This dataset covers the OECD member countries and some non-member countries. In addition to the nominal RPPIs, it contains information on real house prices, rental prices, and the ratios of nominal prices to rents and disposable household income per capita. This dataset contains quarterly and annual statistics for each country. Annual figures refer to the average of the year. Analytical house price indicators. 
Frequency of observation: Annual. 
Measure: Real house price indices. 
Unit of measure: Index, Seasonally adjusted, not calendar adjusted, 2015.