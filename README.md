## Residential Smart Meter Data Analysis
Analysis of residential smart meter data from various sources, including clustering, dimensionality reduction, and comparison between optimal fixed/variable tariffs and the Octopus Agile tariff.

This repo presents a brief analysis on a set of anonymous residential smart meter readings from several hundred meters over a 17-day period, provided by Octopus Energy, at a 30-minute resolution. We will be looking to:
* Quantify various interpolation approaches to handle missing readings
* Explore several approaches to visualising collections of smart meter data 
* Apply some simple dimensionality reduction to improve ease of computation
* Group each household using k-means clustering, and identify any interesting usage trends among and between these groups

Using the Future Energy Associates Taiffscanner API, we will also investigate:
* The potential savings for each household should they move to the Octopus Agile tariff from the average SVT over the measurement period
* Identifying which clusters of consumers would benefit the most from moving to the Agile tariff

Load up the Jupyter Notebook in the `notebooks` directory to follow along.