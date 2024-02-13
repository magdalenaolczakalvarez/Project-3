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

As can be seen, the distribution is left-skewed meaning that the very few listings priced very high influence the distribution shape whereas most of the listings are centered around $100 and is under $200.

From an initial summary data inquiry, the median is $120 and the mean is $194 which is pretty affordable keeping in mind that this is the capital city of the United States. 


Room Types and Price Distribution

The statistics displayed on this graph indicate that 76% of the listings in DC are for a entire home or apartment. Although this could result in higher profits for hosts and Airbnb, it also means that over 4000 potential housing units will not be accessible to residents throughout the year, which may concern housing regulators. Entire home listings have the most potential to disrupt residential communities, remove housing, displace residence, raise housing costs, and conflict with zoning laws. 


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/7e2f554d-8515-439d-8ebc-c71de10c61f7)



In-depth Analysis by Neighborhood 

I have charted the median and mean prices of each neighborhood in Washington, DC, as well as the average prices of the three cheapest and most expensive neighborhoods, to indicate which neighborhood interests me most. 


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/50c69801-bbb1-4216-884c-f0e40403f6a5)


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/c295bf0c-4c19-479d-b2ba-a55497ec21a9)



The Listings host distribution is designed to shows listings each host has on Airbnb. This can be useful for understanding the level of competition among the hosts. 

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/56c83a38-8558-4c9e-8710-22b90b54e34f)


Over time, the number of listings has changed. As you can see from this plot, the number of unique listings in D.C. has increased. In the past few years, there has been a sharp increase, which levels off around 2023.

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/c6d2ad3a-43c1-4009-a9db-57dfb14a240e)



The Sojourn Analysis

Sojourn is an Airbnb host with 231 listings in Washington, DC. 

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/e99a52f0-c440-44b3-9011-fb25c42d4425)

Their listings are located in 45 different neighborhoods, each with varying prices as can be seen in the plot below. 

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/d09bff03-6d0b-41d3-b6f7-76584ba19077)

The average price of all of their listings is $149.28

The average availability of Sojourn' listings is 275 days per year. 

Using the mean price of their listings, the availability and an average occupancy rate of 51.85%, Sojourn'yearly Airbnb revenue is $4,462,916.59.




Licensed or Not 

The law imposing new restriction on short-term rentlas applies specifically to those rentals lastings less than 30 days at a time. Under the new law any D.C. homeowner who wants to rent out a bedroom, basement, or entire home on Airbnb or any other platform has to get a short-term rental license. If the owner is present in the home during the rental, they can host short-term renters as longas they want over the course of each year. But if they are not present (say they are renting their primary home while they are gone during the summer), those rentals are limited to a combined 90 days each year.


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/f1910b3c-abf8-4c2c-8242-a362fd105963)






Conclusion : 

Through my EDA Analysis process, I found some initial insights about the data:



There are 6,853 unique listings in D.C.

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/d3078536-8820-43f5-adaa-7138be3b63d9)


The average price of all listings is $194

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/50e46713-c6a4-48ff-b506-699906a060b6)


Prices ranged from $10 to $1000


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/d219fa18-df42-4e87-abbb-c444f1f8417c)


Average number of listings per host is 2,012


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/e09091ce-3990-4e0c-9b10-4f92174c8294)


One host has 231 listings


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/3fe2d787-daa7-436a-bdef-b9a0e6baf0eb)


Listings are available, on average, 193 days out of the year


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/873da3ce-7916-42fc-b49e-c2d8785734ac)


32% of listings are the sole listing for Sojourn host

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/a641be8c-0818-40ae-bb30-f0cee173263d)


352,242 reviews were written.


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/b0b0d030-9c02-47e6-96cd-fcab0b4034db)


The host "Nicole" received the most reviews. 

![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/98ce5abb-e6b0-41ba-b0d9-82dc181f07ed)


![image](https://github.com/magdalenaolczakalvarez/Project-3/assets/145025544/3aafb978-8e3e-4a9a-a225-2c388678998f)


As a result of my project, I gained quite a bit of information about Airbnb in Washington, D.C., which is going to be very helpful in planning my next trip there. 
There are still many different angles I could take as follow up steps or improvement work on this project. For example, by grouping neighborhoods by wards, I could calculate the average price for each one, allowing me to plan by location and price simultaneously. Additionally, I could use latitude/longitude, different attractions, or distance to mall to find the best host. Nevertheless, due to time constraints, I decided to put it on my next smaller project. 





























