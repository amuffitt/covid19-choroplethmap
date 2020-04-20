# Background

Choropleth maps are an effective visualization method to see variability of a measured value over a geographic area (like the world or a country) using color shades/patterns.  

I found a timely way to learn more about creating static and animated choropleth maps in Python using Plot.ly/Plot.ly Express visualization library by applying it to a dataset showing Covid-19 spread across the world.  These are dynamic maps that zoom in and out and display info on rollover.  The static maps show confirmed Covid-19 cases and deaths as of the most recent date in the dataset, and the animated map shows the world 'status' by date starting on 1/22/2020.  The gradual changing of the colors over time for the companies most affected by Covid-19 is an impactful way to understand these trends over time.

The main reference and source of learning for these visualizations is this intro/tutorial for choropleth maps at https://towardsdatascience.com/visualizing-the-coronavirus-pandemic-with-choropleth-maps-7f30fccaecf5

# Dataset 

The data is from a Kaggle.com dataset at https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset that is ultimately sourced from data collected by Johns Hopkins University Center.  It has information on the number of affected cases, deaths, and recoveries from Covid-19 with data starting on Jan 22, 2020.  I may update this notebook occasionally with the latest data, but the titles of the map charts will show how current the reflected data is.

# Uploaded Files

- Jupyter notebook (Covid Global Spread.ipynb) - This Python notebook goes through importing the csv data, manipulating the dataframes, and showing the static and animated choropleth maps for Covid-19 confirmed cases and related deaths through using Plot.ly Express.  

- covid_19_data.csv - The original csv file that contains the latest data used in the visualizations.
