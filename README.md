# COVID-19 US County Time Series

Data and visualizations to help track the spread of COVID-19 across US counties, updated daily around 1 AM Pacific Time.
Currently the data only includes *confirmed cases*, which may be heavily influenced by the availability of testing.

- Webpage: https://mimisun.github.io/covid19/
- Data: [spreadsheet](https://docs.google.com/spreadsheets/d/1jLAjzYMcsPo71qu5uBxjT_dAzj8vxZfvnTMR-Xp3-v8/)

![timelapse map](http://mimisun.com/covid19_map.gif)

# Acknowledgements
- [UVA](https://nssac.bii.virginia.edu/covid-19/dashboard/) - Main data source. UVA offers downloadable CSV files of daily case counts, and we have collected the US county-level data from those files here for time series analysis and visualization.
- [JHU](https://github.com/CSSEGISandData/COVID-19) - Data source. For the days where county-level data is available from JHU (up until 03/09/2020), we compared their numbers with those from UVA and picked the higher one.
- [data.healthcare.gov](https://data.healthcare.gov/dataset/Geocodes-USA-with-Counties/52wv-g36k) - Lat long coordinates for counties.
- [Google Charts](https://developers.google.com/chart) - Visualization library.

- Other useful resources
  - https://coronavirus.1point3acres.com/en - Real-time updates of number of cases per US county with credible sources.
  - https://covidtracking.com/data/ - Number of tests performed per state and more.
  - https://github.com/beoutbreakprepared/nCoV2019 - Demographics of individual cases, collected from global sources.

