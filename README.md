# Fordgobikes Analysis ~ Summary
Using R-Studio, I download the Ford GoBikes datasets from Lyft API (https://s3.amazonaws.com/fordgobike-data) and analyze the distribution of its rides, given their locations in the Bay Area (San Francisco, Oakland, San Jose). After downloading the files, I cleaned up and merged the 2017 and 2018 datasets. Then I looked at the summary statistics of the data before visualizing the histograms of rider's age distribution with and without outliers, and then based on their sex. Furthermore, I looked at the distribution of rides per month, day and week before geolocating (using k-means clustering method) each ride through Google Map API. I also looked at the distribution of rides' duration per age and location (city). 
# Suggestions
From my analysis I came up with some suggestions. First, the company can capture more data from customers by narrowing the options provided for the date of birth, this will likely reduce the outliers. Second, the map should be updated, especially in the San Jose area as there are a lot of missing values there due to geolocations errors. A research done by Lyft engineering researcher Albert Yuen in "How Lyft Creates Hyper-Accurate Maps from Open-Source Maps and Real-Time Data" (https://eng.lyft.com/how-lyft-creates-hyper-accurate-maps-from-open-source-maps-and-real-time-data-8dcf9abdd46a) provides a good idea on how this can be done. Finally, the data show that in general, mens are riding bikes more frequently while women tend to go for longer ride. It would be nice to find ways for more women to ride bikes, maybe by offering lighter (in weight) bikes. This last point makes it interesting to see women's demand for electric scooters.
