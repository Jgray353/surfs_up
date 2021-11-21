## surfs_up

# Purpose
The purpose of this analysis was to compile weather data for the months of June and December to provide investors so they can better assess potential risk in the investment of a Surf/Shake shop on Oahu Island in Hawaii. 

From a creation perpspective, the purpose was to differentiate between SQLite and PostgreSQL databases, use SQLAlchemy to connect to and query a SQLite database, use statistics like minimum, maximum, and average to analyze data, and to design a Flask application using data.

# Results
In gathering the temperature data, we do see some similarities in weather between June and December. Max temps are within 2 degrees, 85 in June and 83 in December. There are a number of differences, 3 of them being: 

1. The minimum temperature in December (56 degreees farenheit) is 8 degrees lower in December than it is in June (64 degreees farenheit). 
2. The average temperature is 3 degrees lower in December (71 degreees farenheit) as compared to June (75 degreees farenheit).
3. The temperatures in December are lower by at least 3 degrees for each quartile as compared to June (further detail in images below). 
# June temperature data
![alt text](https://github.com/Jgray353/surfs_up/blob/main/June_temp_stats.png)

# December temperature data
![alt text](https://github.com/Jgray353/surfs_up/blob/main/December_temp_stats.png)

# Summary 
If comparing these months for which will do better on ice cream sales, June would win. However, December has enough warm days and isn't significantly colder than June to suggest ice creams would suffer greatly. Additional analysis for precipitation data as well as number of sunny/cloudy days would also be beneficial to better determine how the weather might impact the success of the shop. 
