# Overview 

For this project, we will create a summary DataFrame of the ride-sharing data by city type. Using Pandas and Matplotlib, we will create a multiple-line graph that shows the total weekly fares for each city type. Our analysis will overall cover how the data differs by city type and how those differences can be used by decision-makers at PyBer. We will be using the Pandas groupby() function along with the count() and sum() methods on the DataFrames we will create to gather our overall analysis.

We will be creating:

- a ride-sharing summary DataFrame by city type
- a multiple-line chart of total fares for each city type 

## Results

After merging the city and ride DataFrames, we are able to see all of the data from the three targeted city types (Fig.1). From this, we are able to calculate the total fare for each type of city (Fig.2). After calculating the fares per week, ignoring the null values, we are able to visualize the total weekly fares for each city type. 

**Figure 1: Pyber Data DateFrame**

![Screen Shot 2022-08-22 at 7 23 14 PM](https://user-images.githubusercontent.com/106577074/186055383-36ecc941-2212-477d-b114-565a53379c77.png)

**Figure 2**

![Screen Shot 2022-08-22 at 7 28 34 PM](https://user-images.githubusercontent.com/106577074/186055619-c0f90787-8793-48a8-b9dd-b643fe93444e.png)

Based on our Pyber_Data DataFrame, it seems urban city types had more drivers compared to the total rides. This means that urban drivers had the lowest average fare ride and the average fare per driver was much less than the other two city types. 

In contrast, rural total drivers were faar less than the total rides completed, but the average fare per driver was the highest.

**Figure 3**

![PyBer_fare_summary](https://user-images.githubusercontent.com/106577074/186057642-4f16e1fb-6d5b-4842-bb77-d6e58744fc47.png)

Figure 3 depicts the mulitline graph showing the total fares by each city type. We can see that the fares start to rise late-Februrary and then drop by March. In April, we see that 'Rural' starts to reach its peak again while 'Suburban' had a bit of an increase mid-March, but then just started to decline in later weeks until picking back up in mid-April. 

## Summary 

Based on out findings, the data for all three city types is based upon the population. In more compacted, highly populated areas like urban cities, collects a lower average fare per ride and having more drivers than the total rides in demand. Therefore, the Urban drivers may not have enough work and need to keep their fares at a competitive, low rate. 

Also, fares in rural areas are higher as there are less drivers than the rides in demand. So, the average fare is higher compared to the other two city types. 

Lastly, if PyBer aims to launch any ads or wants to increase their buisness, they shouldn't look for over-populated areas like urban cities, rather go for rural cities and specifically the month of February to kick-start their role within the community.           
