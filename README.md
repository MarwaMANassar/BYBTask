Task : K_means task



Data Source:
The data used in this task was orginally sourced from Help.NGO. This international non-governmental organisation specialises in emergency response, preparedness, and risk mitigation.

Dataset Attributes:
country: name of the country
child_mort: death of children under 5 years of age per 1000 live births
exports: exports of goods and services per capita. Given as a percentage of the GDP per capita
health: total health spending per capita. Given as a percentage of GDP per capita
imports: imports of goods and services per capita. Given as a percentage of the GDP per capita
income: net income per person
inflation: the measurement of the annual growth rate of the Total GDP
life_expec: the average number of years a new born child would live if the current mortality patterns remain the same
total_fer: the number of children that would be born to each woman if the current age-fertility rates remains the same
gdpp: the GDP per capita. Calculated as the Total GDP divided by the total population.
Objective
To group countries using socio-economic and health factors to determine the development status of the country.





table of contents:
Importing libraries
Importing dataset
Checking shape
check data types and counts
descriptive statistics
identify missing data
preprocessing and feature selection
 Drop any non-numeric features (columns)
Create a correlation map of features to explore relationships between features
drawing a heatmap
 Explore the continuous independent features against child_mort using scatter plots.
Explore the continuous independent features against gdpp using scatter plots.
scaling the data
Create a pair plot
selecting k
Kmeans clustering
Fitting a K-Means Model with the selected K value
prediction and visualisation


Installation:
Numpy
Pandas
Sklearn
Matplotlib
Seaborn


Credits: Marwa Nassar- Hyperiondev for the support
