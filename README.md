# airbnb-bookling-analysis
Analyzing the data of airbnb booking system

Airbnb is an open online platform where people list their own housing for rent. Since 2008, it has grown in popularity and especially for those communities which frequently use to travel. It is becoming a strong competitor to the hotel industry. It has millions of listing, which generate lots of data. We are analyzing these data for making business decision, for looking best room type etc.

As a first step we take the overview of data, where we specially made our focus on understanding what each column means. So that we can be clear from what perspective we have to analyze our data. After understanding different column, we marked few important columns. These columns are neighborhood group, room type, price, minimum nights, reviews per month. Then we did some basic visualization to see is there any correlation among columns.
 
Now we started cleaning our data. So we first identified the null values and we replaced these null value according to their data type. After dealing with null values we moved on to those columns which we don’t need. So we removed last review column. Then we replaced few data which don’t make sense with other values. Here we replaced zero price of property with mean price according to their room type and neighborhood type. Finally, our data is ready for EDA.

1.	Price Analysis: The first focus we put on is ‘Price’. Here first we looked in to average price of different room type across New York. From this we get to know that costly room type is ‘Entire home’. Then we looked at average price of room type according to different neighborhood group. From this analysis we made inference that if a salaried employee wants to increase his saving then he will prefer to work in Bronx. Then we did few more on analysis on finding cheapest neighborhood and the cheapest listing throughout New York.

2.	Listing Analysis: Here we focused on different listing. In this we take a look at listing according to their neighborhood group. From the result we made inference that is someone want to do advertisement or marketing he should focus on Manhattan and Brooklyn. Then we deep dive in data and looked different listing according to neighborhood group. We get to know that in Manhattan, entire room type is highly listed.

3.	Availability analysis:  Here we focused on availability of different room according to their neighborhood group and then the average availability of different room type. We get to know that private room has highest availability and entire home has least availability. The inference which come out from this result if host is having entire room then he will be making good money. But from customer point of view private room is the best as half of the year it is available.

