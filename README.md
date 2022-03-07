# SurfsUp

# Background Challenge

The goal of this analysis is to look over a dataset of weather conditions that has been stored in a SQLite database and provide information that will persuade an investor that opening a Surf n' Shake shop in Oahu, Hawaii is a good business idea. The plan is for the shop to sell surf boards and ice cream all year, but the investor is wary because he previously invested in a similar business that failed due to weather conditions. To entice this investor, we must provide statistical analysis, specifically on the weather conditions in Oahu, that will persuade him that this will be a profitable business venture.

To explore the data in the SQLite database, we used SQLAlchemy to connect and generate queries to retrieve the information we needed for our analysis. We used Jupiter notebook throughout this module to import dependencies and create commands to pull data from the SQLite database.

# Summary

An examination of Oahu's weather patterns could aid in determining whether seasons have an impact on the island's surf and ice cream shops. I compared June and December data to describe summer and winter temperatures over a seven-year period in this analysis. The average temperature in June and December was 75°F and 71°F, respectively, during this time period. In June, the low temperature was 64°F and the high temperature was 85°F, whereas in December, the low temperature was 56°F and the high temperature was 83°F. Furthermore, the standard deviations in June and December were roughly comparable. The standard deviation of 3.26 in June and 3.75 in December indicates that their temperature records are concentrated around both of their average temperatures.

# Results
## Deliverable 1

* The average recorded temperature in June is approximately 75 degrees Fahrenheit, which is 4 degrees higher than the average temperature in December.
This corresponds to a -5 percent change in average temperature between June and December.
*The frequency of temperatures recorded in June has a much more normal, tight bell curve distribution, which is supported by the lower standard deviation of June temps vs December temps.
*Temperatures in December appear to be more variable than those in June, owing to the larger range of recorded temperatures (comparing the maximum vs min temp of each month).

## Deliverable 2

*The average temperature difference between summer and winter is less than 4 degrees. This demonstrates that the weather isn't very variable all year, and it's rarely too cold for a scoop of mint-chocolate chip ice cream and some tight curls.
*Most temperature observations were within 4 degrees of this average on either side. This indicates that the majority of days are within a few degrees of the average, and that the average temperature is not unusual. You are unlikely to encounter freezing waves, and your double-scoop cone of rocky road is unlikely to melt before you can eat it.
*Less than 3/4 of the daily rainfall readings for three years indicate less than 0.14 inches. This data, modified from the work done on the module, shows that the average rainfall is very low. So you don't have to worry about bad weather on the beach or  unwanted raindrops on Triple Sunday.
