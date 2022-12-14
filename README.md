# PyBer_Analysis
Exploratory data analytics for Pyber (Python-based ridesharing app company), using the  Pandas software library, Matplotlib (plotting library for the Python programming language) and interactive computational environment Jupyter Notebook
## Results
Importing data from  CSV files and writing Python scripts, main purpose of this analysis is to create a variety of charts that showcase the relationship between the type of city and the number of drivers and rides, as well as the percentage of total fares, rides, and drivers by type of city in order to help Pyber improve access to ridesharing services and determine affordability for underserved neighborhoods.
After collecting the data (using the Pandas read_csv function and the OS module), next steps were, preparing and cleaning data for analysis, using summary statistics on the data as a whole and on individual columns, drilling down to specific rows, columns, and subsets of the data to make a comparison between the different city types. ([PyBer_Analysis](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/PyBer.ipynb)     [PyBer_Challenge](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb))
* In order to make comparison of the selected data scatter plot was created  for each type of city.
-  [x] The x-axis is the number of rides for each city.
-  [x] The y-axis is the average fare for each city.
-  [x] The size of each marker is the average number of drivers in each city.
-  
![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig1.png)

Looking closely at the graphic data, we can conclude that the main source of revenue for Pyber comes from Urban cities. ( The number of drivers and overall number of rides are significantly higher than in Suburban and Rural cities).


* To present more in depth statistic, pie charts were used in this analysis 
![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig5.png)
![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig6.png)
![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig7.png)

* One of the tasks was to find out if there were any outliers in the dataset . For this part of the analysis the box-and-whisker plot was used.
 There is one outlier in the urban ride count data (West Angela city has the highest rider count). Also, the average number of rides in the rural cities is about 4 and 3.5-times lower per city than the urban and suburban cities, respectively. There where no outliners in [Ride Fare Data](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig3.png) and [Driver Count Data](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig4.png).
 ![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig2.png)
 
 * Multiple-line chart  was created to showcase each weeks peak or dip in Total Fares by City Type for selected time period. This data will be used to plan the number of drivers needed in the future for specific dates (day, week, month) of the year.
 
 
 ![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

 ### Summary 
 Summarizing data and addressing disparities among the city types, there are some following recommendations to the  PyBer CEO:
 * Increase number  of drivers during peak days of the  week (plan to increase the number of drivers during peak months and decrease the number of drivers during "slow" months of the year).
 * Adjust fares for specific days - week when rides count are exceptionally high (example - holidays)  and types of cities (make incentive for suburban cities to use Pyber services more often).
 * Add more drivers to West Angela city (by relocating drivers from neighboring Suburban cities or employing more drivers).
