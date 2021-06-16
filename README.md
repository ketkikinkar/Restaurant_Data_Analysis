# Restaurant_Data_Analysis

### Introduction
Restaurant data analysis is one of the most useful analyses for foodies who want to taste the best cuisines of every part of the world which lies in their budget. This analysis is also for those who want to find the value for money restaurants in various parts of the country for the cuisines. Additionally, this analysis caters the needs of people who are striving to get the best cuisine of the country and which locality of that country serves that cuisines with maximum number of restaurants

### Motivation
It is very common that we hang out with families, friends, and coworkers when comes to lunch or dinner time. As the users of recommendation applications, people care more about how we will like a restaurant. People will tend to have happier experiences when the prediction of the recommendation system is as good as what it says. As there is a completed and big data set of user and restaurant reviews, we want to see whether we can use the latest techniques to make good predictions. In the data set, there are not only reviews but also relevant information of users and restaurants that allow us to do more complicated computation, which might lead to the construction of a better model.

### Problem Statement

In  the  past,  people  obtained  suggestions  for  restaurants  from  friends  or  other  conventional sources or sites. Although this method is straightforward and user-friendly, it has some severe limitations.  First,  the  recommendations  from  friends  or  other  common  people  are  limited  to those places they have visited before. Thus, the user is not able to gain information about places less  visited  by  their  friends.  Besides  that,  there  is  a  chance  of  users  not liking  the  place recommended by their friends. Second, the information provided by the site can often be biased; thus the information provided cannot always be considered accurate. Our primary aim is to do data visualization with the help of matplotlib and Power BI and perform operations with MapReduce. 

### Objective:
The main objectives of the application are:
- To collect user ratings on the cuisines  of different restaurants.
- To  recommend  restaurants  and  foods  to  users  based  on  their  user  ratings  using collaborative filtering algorithm.
- To check online delivery systems of different restaurants.
- Location of the restaurant is an important factor to be considered when building a restaurant recommendation system. Location will be used to filter the restaurants from a top list.
 
### Tools used:

#### Python: 
We have used python for the main code in which we have used pandas numpy and matplotlib and have imported yelp.csv to show various kinds of visualizations which will be shown below.

#### MongoDB: 
MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas. 
We have used mongodb to do the mapreduce part of the code. Map-reduce is a data processing paradigm for condensing large volumes of data into useful aggregated results. To perform map-reduce operations, MongoDB provides the mapReduce database command.

#### Powerbi: 
Power BI is a business analytics service by Microsoft. It aims to provide interactive visualizations and business intelligence capabilities with an interface simple enough for end users to create their own reports and dashboards. It is part of the Microsoft Power Platform. 
In Power Bi we have imported a csv file “restaurant.csv” using the data in it we have made various visualizations which will help users to choose the restaurants and have a happy meal. 

### Dataset Description
Fetching the data:
Data has been collected from the Kaggle in the form of .json files(raw data) using the url=https://www.kaggle.com/shrutimehta/zomato-restaurants-data?select=file5.json
 
### Data Storage:
The collected data has been stored in the Comma Separated Value file Yelp.csv. Each restaurant in the dataset is uniquely identified by its Restaurant Id. Every Restaurant contains the following variables:

• Restaurant Id: Unique id of every restaurant across various cities of the world

• Restaurant Name: Name of the restaurant

• Country Code: Country in which restaurant is located

• City: City in which restaurant is located

• Address: Address of the restaurant

• Locality: Location in the city

• Locality Verbose: Detailed description of the locality

• Longitude: Longitude coordinate of the restaurant's location

• Latitude: Latitude coordinate of the restaurant's location

• Cuisines: Cuisines offered by the restaurant

• Average Cost for two: Cost for two people in different currencies 

• Currency: Currency of the country

• Has Table booking: yes/no

• Has Online delivery: yes/ no

• Is delivering: yes/ no

• Switch to order menu: yes/no

• Price range: range of price of food

• Aggregate Rating: Average rating out of 5

• Rating color: depending upon the average rating color

• Rating text: text on the basis of rating of rating

• Votes: Number of ratings casted by people
