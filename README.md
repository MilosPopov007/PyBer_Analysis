# PyBer_Analysis
Exploratory data analytics for Pyber (Python-based ridesharing app company), using the  Pandas software library, Matplotlib (plotting library for the Python programming language) and interactive computational environment Jupyter Notebook
## Results
Importing data from  CSV files and writing Python scripts, main purpose of this analysis is to create a variety of charts that showcase the relationship between the type of city and the number of drivers and rides, as well as the percentage of total fares, rides, and drivers by type of city in order to help Pyber improve access to ridesharing services and determine affordability for underserved neighborhoods.
After collecting the data (using the Pandas read_csv function and the OS module), next steps were, preparing and cleaning data for analysis, using summary statistics on the dat a as a whole and on individual columns, drilling down to specific rows, columns, and subsets of the data to make a comparison between the different city types.
* In order to make comparison of the selected data scatter plot was created  for each type of city.
-  [x] The x-axis is the number of rides for each city.
-  [x] The y-axis is the average fare for each city.
-  [x] The size of each marker is the average number of drivers in each city.
![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig1.png)

Looking closely at the graphic data, we can conclude that the main source of revenue for Pyber comes from Urban cities. ( The number of drivers and overall number of rides are significantly higher than in Suburban and Rural cities).


* To present more in depth statistic, pie charts were used in this analysis 
![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig5.png)
![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig6.png)
![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig7.png)

* One the tasks was to find out if there were any outliers. For this part of the analysis the box-and-whisker plot was used.
 There is one outlier in the urban ride count data (West Angela city has the highest rider count). Also, the average number of rides in the rural cities is about 4 and 3.5-times lower per city than the urban and suburban cities, respectively. There where no outliners in Ride Fare Data and Driver Count Data.
 ![This is an image](https://github.com/MilosPopov007/PyBer_Analysis/blob/main/analysis/Fig2.png)

 
