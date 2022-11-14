# World_Weather_Analysis

#### Objective
The purpose of this project was to ultimately create an application that a person could use to plan a trip based on climate criteria. In this case, I considered minimum and maximum temperatures that the user would provide. From there, a dataframe would be produced that listed every city in the world that fit the user's criteria. Then, the available hotels in each of those cities would be added to the dataframe by proximity. This would prevent anyone from having to commute too far from their city of interest and their lodging. Finally, an itinerary was created that would provide a route to travel between each city of interest.

#### Challenges
To date, this is the most challenging project I have completed. It involved using APIs from multiple web hosts, writing multiple programs to gather, format, print, and save data. Primarily, this involved converting JSON objects from the web hosts into Pandas dataframes. I produced the figures with the gmaps package, which was useful because it allowed me to implement Google Maps figures with place markers and relavent information. In order to generate latitude and longitude coordinates, I implemented Numpy's random.uniform() method, which were then zipped into tuples. These tuples would then be used to create the initial set of cities.

#### Results
Ultimately, I was able to create an itinerary that a person could follow to travel in Indonesia. Strangely, no cities in the United States appeared in the final dataframe of eligible cities, with the exception of Hawaii and Corpus Christi, TX. It is possible that this was a result of the random.uniform() method, the temperature criteria I entered, or both. It would be interesting to see how the entire process goes if I were to restart from the beginning. 

#### Future Improvements
As it stands, this project only takes temperature criteria from the user. In a final version, I would want the application to consider a lot of different criteria, such as humidity, hours of daylight, average cost per week of travel, etc. It would also be helpful to pair this with an application for flights that could consider travel time, airfare, and available flights. However, this first step is a significant start and a proof-of-concept. 
