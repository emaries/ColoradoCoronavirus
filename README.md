# ColoradoCoronavirus
Statistical Analysis of Colorado COVID-19 Data from Feb 2020 - Jan 2021

I used  Colorado’s COVID-19 Case Surveillance Data to answer some questions regarding the correlation between testing rates and positive test rates (in response to Donald Trump’s assertion that “testing creates cases”) and holiday effects on infection. The dataset features multiple aggregations of positive COVID test percentages (3-day average, 7-day average, a “Percent Positivity” taken every Monday and Friday) along with the types of tests used, dates attributed to each test, locations of each test (whether it was a state clinic or private). There is also a measure of total tests given each week per every 100,000 Coloradans. There are 5,097 rows of observations from April 2020 to January 2021. 

Because the dataset put all of the aforementioned categories in a single column with a “value” column next to it, I had to use pivot tables to organize the metrics I needed - “Percent Positivity”, “Total Tests Per 100K”, “attr_date” (which I aggregated into a holiday and non-holiday binary) and “number of positive tests”.
