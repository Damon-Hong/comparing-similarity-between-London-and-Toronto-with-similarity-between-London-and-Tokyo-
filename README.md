# comparing-similarity-between-London-and-Toronto-with-similarity-between-London-and-Tokyo-
# Introduction:
In this project, the similarity between London and Toronto and the similarity between London and Tokyo are compared in terms of the categories of venues in each neighbourhoods of these three major cities of respective countries. As we all known, London and Toronto are biggest cities of United Kingdom and Canada which are both Western countries. However, Tokyo is the capital city of Japan which is a Asian countries. Therefore, it is very interesting to investigate whether there is difference between the structure of Asian major city and Western major city. In this project, we choose London as the main object, and study the similarities between Canada and Japan with respect to London. 
# Data:
In this report, the borough and neighbourhood of London, Tokyo and Toronto are extracted from wikipedia websites. 

*borough and neighbourhood of London*: https://en.wikipedia.org/wiki/London_boroughs 

*borough and neighbourhood of Tokyo*:https://en.wikipedia.org/wiki/Special_wards_of_Tokyo

*borough and neighbourhood of Toronto*:https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

For each neighbourhood, geopy library has been used to obtain latitude and longitude information. 

Next, Foursquare dataset is used to get the venues information of each neighbourhood with limit 100 and radius 500 meters. For instance, venue name, venue latitude and longitude, venue category. Hence, we can group neighbourhoods in terms of the venue categories and frequences of each categories. Therefore, using the data visualisation techniques, we can obviously compare the similarity between London and Toronto with the similarity between London and Tokyo.

# Conclusion:
From the cluster visualisation map, there is a obvious result. We have grouped neighbourhoods from London, Tokyo and Toronto into 6 clusters. In the result, the neighoburhoods in London most likely belong to cluster 3 and cluster 1. The neighbourhoods in Toronto most likely belong to cluster 3 and cluster 1 as well. However, the neighbourhoods in Tokyo most likely belong to cluster 2 and cluster 3. Moreover, The most common cluster in both London and Toronto is cluster 3 and then cluster 1. There are least cluster 2 in those two cities. However, the most common cluster in Tokyo is cluster 2 and then cluster 3. Furthermore, there may be no cluster 1 in Tokyo. Therefore, we can conclude that the similarity between London and Toronto is apparently larger that the similarity between London and Tokyo.
