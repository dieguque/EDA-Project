# MTA subway demand during COVID-19
Diego Duque

## Abstract
The goal of this project was to find if COVID-19 has affected the Metropolitan Transportation Authority (MTA) subway system in New York City’s demand. To make this possible, the [turnstile MTA public data](http://web.mta.info/developers/turnstile.html) was used. On this public data, each subway station has at least one turnstile; but in most of the cases they have multiple turnstiles that track the number of people getting in and out through the turnstiles. This was they key factor to measure and graph the demand.  I used Python to make it possible.

## Design
A hypothetical situation was created where the Department of Transportation is aware that due to the current COVID-19 pandemic many things have changed; including public transportation. Consequently, the Metropolitan Transportation Authority (MTA) has requested emergency funding from the Department of Transportation arguing that they ran out of economic resources and the MTA profit represented 85% of the subway system’s income before the pandemic. In this hypothetical situation I have been asked to analyze the [MTA turnstile public data](http://web.mta.info/developers/turnstile.html) and graphically present if there are any substancial changes on the MTA subway demand.

## Data
The data includes all the turnstiles from all the stations that meet the requirements that I have placed. The requirement I have set is as follows: individual turnstiles that have a maximum of 43,000 entries per day. This number was calculated by assuming one person enters the turnstile every 2 seconds in order to omit outliers from faulty turnstiles that might skew the results. The other requirement set was that data was to be taken from January 2019 to May 2021. This time span was chosen to compare data yearly from before and during the pandemic. This accounts for 868 days of data exactly. The dataset contains 2,670,720,161 users during this period of time.

## Algorithms
The open-source software Jupyter Notebook was used running Python tools to clean, aggregate, and visualize the data.

## Tools
  - Pandas, Datetime and Numpy for data manipulation.
  - Matplotlib, Seaborn, Numpy, and StatsModels for plotting

## Communication
By using [this link provided](https://github.com/dieguque/MTA/blob/27b3c378176d4ade8fc5151bc39b96b2255859c5/MTA%20demand%20during%20covid-19.pdf), the slides used during the presentation may be accessed. On the graph below, I have summarized the project findings.

![](https://github.com/dieguque/MTA/blob/6691ba870fd38c6fa2fae74a5322add94fc74d72/MTA_entries1.png)
