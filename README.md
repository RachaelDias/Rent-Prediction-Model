# Rent Prediction Model

In this project data was scraped from housing website Zoocasa using Python's packages BeautifulSoup and Selenium. The addresses were geoencoded using the Google Maps API.
In addition to this the walkscore for each addresses was extracted using walkscore API. Finally, a linear regression model was developed using sci-kit learn to estimate the price of a rental based on no. of bedrooms, no. of bathrooms, no. of parking spots, no. of garage spaces, size, and walkscore.

Python Libraries: requests, Selenium, BeautifulSoup, googlemaps, walkscore, pandas, numpy, matplotlib, seaborn and scikit-learn
R packages: tidyverse, dplyr, forcats, ggplot2, readr, highcharter, kableExtra, htmlwidgets

