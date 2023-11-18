# 2018_Seattle_Airbnb_Rentals

# Context
Seattle , also known as Emerald city is famous metropolitan city in the united states and it’s home to a large tech industry which includes Amazon , Microsoft, Expedia ,Starbucks and many more.

As an avid traveller ,I was really fascinated to check the Airbnb usage by touriest through out the year in Seattle.This would help to have more precise idea whenever we travel to Seattle. Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA.



# Business Questions
a) Room availability through out the year in Seattle.

b) Mean prices analysis per month.

c) Price detection on the basis of available dataset.


# Analysis 
After the data exploration and analysis , following is the analysis I was able derive:

a) Room availability through out the year in Seattle:

![image](https://github.com/pranavhonrao9/2018_Seattle_Airbnb_Rentals/assets/131235099/527e8e7b-efe3-441e-bacb-47a723a5c73d)


From the above graph, I can see January ,Feburary has less rooms available which make sense to me. As people would not prefer to put home on airbnb becuase of winter season. Also, in summer days Seattle being one of the famous cities to visit ,less rooms are avaiable.

Interesingly , room availability do not vary that much beside March and December. I think ,in march people start putting there home on Airbnb listings but do not get that much of response causing high number of rooms avaiable. This is maybe because ,people travel less during that period. Surprisingly for December, room availability is high.

b)Mean prices analysis per month:

![image](https://github.com/pranavhonrao9/2018_Seattle_Airbnb_Rentals/assets/131235099/c9f4baf0-acc4-4d29-847e-31512d7ea0a5)


From above figure , we can get precise idea about mean prices analysis per month ,when prices are low in the winter and high in summer period.

c)Price variance with the number of bedrooms:

![image](https://github.com/pranavhonrao9/2018_Seattle_Airbnb_Rentals/assets/131235099/479ee3bc-6ea2-4f32-9e61-086d9ddd2128)

As expected , number of bedrooms is one of the prime feature to determine the price of the house. More the number of bedrooms ,looks like having highest price and lower the number of bedrooms has the lower number of prices.

d)Price detection on the basis of available dataset.


MSE train: 445.4331, test: 1938.0942
R^2 train: 0.9426, test: 0.6880
As for the prediction  of prices , I was able to get the value if R^2 near about to 70%. With the less data being one of the prime roadblock to achieve more accurate results. As we are finding the continous value of the price, regression algorithms were used for the prediction.


For more details, blog link: https://medium.com/@honrao.pranav/interesting-facts-about-seattle-airbnb-usage-in-2016-7d3e20e81e82
