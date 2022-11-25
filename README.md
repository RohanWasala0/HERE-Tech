# herehack_s5_Three

# Gathering Data
Web scraping on Wikipedia will be used for learning purposes. We will be working directly with the neighbourhoods and ignore all the districts because that will help in more granular analysis of the areas.

Geospatial data- To analyse venues present in each neighbourhood, we will be targeting residential areas. Using the HERE Geocoding & Search API, we will be able to explore different venues. Before using HERE API, we need to convert the neighbourhood names into pairs of latitude and longitude coordinates.

Census data- Census data will help us find out the population of the and the average income of the location.

# Model
The elbow method is used to determine the total number of clusters that can be made in a dataset. For the k means clustering, the clusters has to be predetermined to form the clusters and that's why we use elbow method to determine the number and the total clusters made in the neighbourhood venues. We create a data frame using top venues and cluster labels.

In k means clustering we will predetermine the number of clusters. We will be making groups of cluster based on the distance between the points(minimum distance). If these cluster of points are similar to each other in some way, they form a cluster. There is a high chance of the results affecting because of the outliers so we need to be vary of them in order to get an accurate result.


# Methodology

Scrapping Wikipedia
Creating a dataframe for training
Getting geographical coordinates for the neighbourhoods
Requesting HERE Geocoding & Search API for geospatial data
Analysing each neighbourhood
Grouping rows by neighbourhood and finding frequency of each category
Loading census data file
Population and Household income by neighbourhood
Finding optimum number of clusters by the elbow method
Run k-means to cluster the neighbourhoods into optimal clusters.
Selecting a cluster
Counting supermarkets in residential neighbourhoods
Calculate proportion of markets
Scatter plot with income vs people per market

# Results 
In the above made scatter plot, the highlighted area in green represents the most adequate areas to open a low-cost supermarket since their household income is below average and also their ratio of people per market is above average.

# Conclusion
The neighborhoods/ towns of the selected locations were analyzed with the purpose of finding the ideal location for a new low-cost and profitable supermarket. We applied machine learning techniques such as k-means clustering to identify the key types of venue that define a residential area such as schools, pharmacies, small markets and corner shops, and the types of venue that discard a residential area such as night clubs, theaters and so on.  Further data such as population and market venues have been used to reduce the number of potential areas.
