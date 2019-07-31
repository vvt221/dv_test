# Data Visualization Final 2019

## Team Member : Vaidehi Thete (vvt221)

## Tasks Chosen:

2. For those trips that could not be served, do they follow a spatial or temporal pattern? For example,
are most of those trips originated in particular regions, and of certain times?

4. We also limit vehicle capacity to at most 4 passengers. Were there vehicles violating this condition? If
so, can you show any pattern about these vehicles? For example, how many of them were violating,
and where were they distributed in both time and space?

## Links to Visualization and Short Explanation:

### Task 2: For those trips that could not be served, do they follow a spatial or temporal pattern? For example, are most of those trips originated in particular regions, and of certain times?


#### Plot 1:

https://bl.ocks.org/vvt221/7308a3becd0c42c40a22ff735f3fb555

#### Explanation:
From the plot it can be seen that a majority of the trips are not served in the early hours of the morning from 12.00 AM to 4.00 AM. However, this trend suddenly drops between 5.00 AM and 11.00 AM . This could be because this is the time duration around which people commute to their workplaces and they cannot afford to be late which is why the number of trips where the rides are dropped is low. There is once again an increase in the number of trips dropped. However there is a sharp decline in the number of trips dropped at 9.00 pm ,which could be due to people wanting to reach home as early as possible. The high percentage of ride dropping during the hours discussed above could be due to the high price being charged during these hours but data is not available to verify that.


#### Plot 2:

https://bl.ocks.org/vvt221/361d67866f021d266f52fd930f7792bb

#### Explanation:
This plot shows the bar charts based on the counts of the Actual_Pickup station where most rides could not be served. The counts are then sorted in decreasing order of their frequency. Station ID 229 and Station ID 1196 hold the record for having the highest number of dropped records. Further exploration is done in the spatial plot below:

#### Plot 3:

https://bl.ocks.org/vvt221/89551b051b549965b8ac67b375280bbd

#### Explanation:
This plot shows the number of dropped rides at census tract level in Manhattan. From the plot we can see that a large number of rides are dropped in the Central Park region. There are few census tracts near the financial district which hace a high drop rate. Another region with a high ride drop rate is the area in the upper regions of Manhattan.



### Task 4: We also limit vehicle capacity to at most 4 passengers. Were there vehicles violating this condition? Ifso, can you show any pattern about these vehicles? For example, how many of them were violating,and where were they distributed in both time and space?

#### Plot 1:

https://bl.ocks.org/vvt221/8bf02bece90b84e4d349cc51645e23d0

#### Explanation:
This plot shows the hourly distribution of counts of rides where the number of passengers exceeded 4. There are a lot of such rides during the late night hours and early morning hours. But the number is less during the morning and afternoon hours.
It could be possible due to garbage values because the passenger count exceeds 10 and goes on till 68 which are probably garbage values.


### Plot 2:

https://bl.ocks.org/vvt221/dc8610c07a8ba2818e291a37eacc89f6

#### Explanation:
This plot shows the number of passengers exceeding 4 varies throughout the hour of the day and pretty much is consistent with the above plot but can be used to see how the distribution varies hourly at a granular level.


### Plot 3:



#### Explanation:







