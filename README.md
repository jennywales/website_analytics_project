# Website Analytics Project

This project originally used data downloaded from Google Analytics to analyse seasonal trends in applications to a website, 
and to predict future applications using a time series model. The project also used data on partner companies provided by the 
client to answer questions around hiring trends in the industry.

# Project Brief

Part 1:
The client would like to be able to predict application volumes for a course for a given month. They suggest that there may be 
a correlation between traffic volumes on the website and application volumes. Other metrics may be info session clicks and 
info pack submissions. They would like these questions answered:

1) Are there trends or seasonal patterns in the metrics (sessions, booking info sessions, info pack submissions and 
applications)? e.g. are particular days of the week more popular for people applying or booking info sessions?
2) Compare FY 2017/2018 and 2018/2019 for the metrics. 
3) Predict 2019/2020 for the above metrics
4) Correlation between trends in these metrics.

Part 2:
The client has a data set on industry partners and where students are employed after finishing the course. The client would 
like these questions to be answered, as well as any other interesting trends that can be identified:

- What is the total amount of each sector where we place a student?
- What is the gender split in these sectors?
- What is the average age in these sectors?
- What are the top 5 most popular sectors?
- What are the bottom 5 sectors?
- Who are the top 10 best business recruiting?
- What are the trends for each year a student graduated vs business area placed?

# Features

The website data was originally downloaded using GoogleAnalyticsR, while the partner data was provided in csvs. For 
confidentiality reasons the data has been synthesised using Mockaroo and synthpop.

The analysis was carried out in RStudio, with graphs being made using ggplot and the time series model being built using
the package tseries. The analysis was presented in a keynote presentation.

See documentation for further details on the analysis done and the insights made.

# Credits

This project was done as part of the Data Analysis course at CodeClan.
