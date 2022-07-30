# surfs_up
Using SQLite and Flask for climate Analysis 

# Overview of the analysis

The purpose of this analysis is to explore the data in the SQLite database containing the weather conditions that has been stored. This information supposes to convince an investor to open the shop on Oahu, Hawaii. In order to get this investor on board, we need to provide statistical analytics specifically on the weather conditions in Oahu that will convince him that this will be a successful business venture.

**Used tools:**
Jupyter Notebook
SQLite
SQLAlchem
Flask

# Results

I examined weather trends on Oahu:

* accessed meteorological data from the 6 meteorological stantions:

![img5.png](/images/img5.png) 

* wrote queries to examine temperature data collected in the months of June and December,
* calculated summary statistics (especially min, max, and average temperatures collected).

![img1.png](/images/img1.png) 

![img2.png](/images/img2.png) 

* The average temperature is 71-75 farenheit.
* Both June and December showed similar min/max and average temperatures.
* We can safely assume that the temperature does not have dramatic fluctuations through the year.


# Summary

In summary, the temperature in Oahu is relatively the same through the year and the chances of continuous rainfall is low. When we rewrite the queries to add precipitation to the results for June and December, the average precipitation in those months showed:

![img3.png](/images/img3.png) ![img4.png](/images/img4.png) 

* June at 14%
* December at 22%

Looking at the precipitation and the temperature proves that investing in **Surf&Shake** is a good business venture and that Oahu, Hawaii is the ideal location.

