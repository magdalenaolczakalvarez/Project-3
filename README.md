# Project-3

Description


The popularity of Airbnb has skyrocketed over the past decade. A tool that allows travelers to experience destinations like locals instead of tourists. Homeowners also use it to make some extra money by renting out rooms or entire properties. Whether for the better or for the worse, Airbnb has transformed the travel and short-term rental industry.
Considering that my new job requires me to travel to Washington D.C and other places throughout the year, I decided to do an Airbnb analysis to see where I should book my next stay that is both affordable and convenient. 


Data 

The data used in this project comes from InsideAirbnb.com. This site houses datasets for Airbnb information on cities around the globe. The tool scrapes Airbnb data to answer my question, as a potential guest, of where are the most affordable, well-rated and well-reviewed listings, and as a courtesy, I'd like to see how Airbnb data affects a city's housing landscape. The data they provide is extremely useful for addressing those questions. 


There are four csv files per city available on this site for download: Listings, Neighborhoods, Reviews, and Calendar. Each dataset contains different information with some overlap.

Neighborhoods: This includes a list of defined neighborhoods as well as a geojson file that defines each neighborhood's boundary coordinates.

Listings: The listings dataset includes the bulk of the data-listing names, locations (latitude/longitude), neighborhoods, hosts, room types, prices, minimum nights the listing must be booked for, the number of reviews for that listing, the date when the last review was written, the average number of reviews per month, availability (number of days out of 365 the listing is available for booking), and the number of listings per host.

Reviews: There are almost 505,377,000 reviews associated with unique listing ids. These are the same listing ids as in the Listings dataset. The dates of these reviews range from January 2023 to the time the data was collected.

Calendars: This dataset represents a ‘calendar’ of prices and listings for each day for the following year (from the time the data was collected).




Data Analysis



I started the analysis by looking at the General Distribution of the Prices to get a feel for the pricing landscape:
Because 79% of listings fell under $300 per night, in my opinion the most affordable price, I plotted the distribution within this range for better visibility:

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/bdc4875b-c0d3-4347-8894-e48bbbf1be49)

As can be seen, the distribution is right-skewed meaning that the very few listings priced very high influence the distribution shape whereas most of the listings are centered around $100 and is under $200.

From an initial summary data inquiry, the median is $120 and the mean is $194 which is pretty affordable keeping in mind that this is the capital city of the United States. 


Room Types and Price Distribution

The statistics displayed on this graph indicate that 76% of the listings in DC are for a entire home or apartment. Although this could result in higher profits for hosts and Airbnb, it also means that over 4000 potential housing units will not be accessible to residents throughout the year, which may concern housing regulators.

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/7e2f554d-8515-439d-8ebc-c71de10c61f7)



In-depth Analysis by Neighborhood 

I have charted the median and mean prices of each neighborhood in Washington, DC, as well as the average prices of the three cheapest and most expensive neighborhoods, to indicate which neighborhood interests me most. 


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/50c69801-bbb1-4216-884c-f0e40403f6a5)


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/c295bf0c-4c19-479d-b2ba-a55497ec21a9)





The Listings host distribution is designed to shows listings each host has on Airbnb. This can be useful for understanding the level of competition among the hosts. 

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/56c83a38-8558-4c9e-8710-22b90b54e34f)






Over time, the number of listings has changed. As you can see from this plot, the number of unique listings in D.C. has increased. In the past few years, there has been a sharp increase, which levels off around 2023.

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/c6d2ad3a-43c1-4009-a9db-57dfb14a240e)


Additionally, the total number of comments has changed over time, the graph below show that quantity of comments/reviews for listings in D.C has increased.
 

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/370f974c-9907-4a3a-829d-f4ca9c2cc3b5)


This plot shows sharb increase around 2023 that was seen above in the listings plot. 




Housing

The statistics displayed on this graph indicate that 76% of the listings in DC are for a entire home or apartment. Although this could result in higher profits for hosts and Airbnb, it also means that over 4000 potential housing units will not be accessible to residents throughout the year, which may concern housing regulators.

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/7e2f554d-8515-439d-8ebc-c71de10c61f7)

The Listings host distribution is designed to shows listings each host has on Airbnb. This can be useful for understanding the level of competition among the hosts. 

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/56c83a38-8558-4c9e-8710-22b90b54e34f)


The Sojourn Analysis

Sojourn is an Airbnb host with 231 listings in Washington, DC. 

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/e99a52f0-c440-44b3-9011-fb25c42d4425)

Their listings are located in 45 different neighborhoods, each with varying prices as can be seen in the plot below. 

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/d09bff03-6d0b-41d3-b6f7-76584ba19077)

The average price of all of their listings is $149.28

The average availability of Sojourn' listings is 275 days per year. 

Using the mean price of their listings, the availability and an average occupancy rate of 51.85%, Sojourn'yearly Airbnb revenue is $4,462,916.59.


















