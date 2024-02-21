# **NYC Airbnb Data Analysis**

**Let's work with different types of file formats by learning about the New York City Airbnb marketplace. And let's start acquiring basic data preprocessing skills.**

### *What will we learn?*

> 1. Importing the Data
> 2. Cleaning the price column
> 3. Calculating average price
> 4. Comparing costs to the private rental market
> 5. Cleaning the room type column
> 6. What timeframe are we working with?
> 7. Joining the DataFrames.
> 8. Analyzing listing prices by NYC borough
> 9. Price range by borough
 

### *Let's get to know data sets*

New York City is the most populous city in the United States and one of the most populated metropolitan areas in the world. Accordingly, we will work on 2019 Airbnb listings that people have used for their accommodation needs.In this notebook, we will be working with different types of files containing NYC Airbnb market information, these are .csv and .xlsx.

#### *airbnb_price.csv*

**listing_id:** The unique id number of listing

**price:** Nightly accommodation fee in dollars

**nbhood_full:** The borough and neighbourhood where the listing is located

#### *airbnb_last_review.csv*

**listing_id:** The unique id number of listing

**host_name:** Name of the host

**last_review:** Last review date

#### *airbnb_room_type.xlsx*

**listing_id:** The unique id number of listing

**description:** Apartment description

**room_type:** Room type

The main purpose is to get meaningful results by recognizing the data. In the process, it is to transform the irregular and unprocessed data into a correct and interpretable data.

* What is the average price, per night, of an Airbnb listing in NYC?
* How does the average price of an Airbnb listing, per month, compare to the private rental market?
* How many adverts are for private rooms?
* How do Airbnb listing prices compare across the five NYC boroughs?

  ## <center></center>
### <div style="color:white;display:fill;border-radius:5px;background-color:#75B7BF;letter-spacing:0.1px;overflow:hidden"><p style="padding:20px;color:white;overflow:hidden;margin:0;font-size:100%;text-align:center"> Conclusion </p>

    
#### We tried to obtain meaningful data by working on the Airbnb data set of New York City for 2019. 
    
* We noticed that houses with the same features in different parts of the city have different accommodation prices. This shows us that a different real estate market dominates between the districts. 
    
* In addition, accommodation fees increase in more economically active regions. As a reflection of the supply and demand balance, its effect on real estate and accommodation prices is directly observed in the data set.
    
* When the houses in the same region are compared according to the room types, they act with a certain correlation with the fees.
    
* Airbnb gives us an idea of how people's comfort zones and private life preferences are shaped. When we make a distribution according to the room types, it is seen that the shared room type is the least preferred. 2.32% of the room types in the data set are shared rooms. 

ref: https://projects.datacamp.com/projects/1354
