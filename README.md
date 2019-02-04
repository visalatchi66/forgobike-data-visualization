# Forgobike-data-visualization

## Source of dataset:
The dataset is 2017-fordgobike-tripdata.csv and was found in https://s3.amazonaws.com/fordgobike-data/index.html.

## Investigation Overview:
In this investigation, I want to look at how factors such as age group, gender, user type and whether the start station and end station are same will influence the frequency of bike rental and duration taken.

## Dataset overview:
The original dataset consists of duration,start time, end time, information about start station and end station,latitude,longitude,bike id,user type,member birth year and member gender. 

## Data Cleaning and adding columns:
The data is cleaned and columns such as age,age group and whether the start station and end station are same are added to the dataset to have a deeper analysis.Age is calculated by subtracting 2017 from member birth year.The age group is categorised as young who are less than or equal to 30,middle aged who are between 30 and 50 and old who are greater than 50.'start=end' column is included to categorize whether the start station being equal to the end station is true or false by comparing the station ids.

## Summary of steps involved:
The frequency of start station and end station being equal and not equal is first found out.Then the median duration of both are compared.The correlation of the variable with other variables are also found out.The frequency of all the categorical variables like age group,gender,user type and the inter correlations are observed.How these variables affect the duration is noted down.The quantitative correlation between age and duration is highlighted. 

## Exploratory analysis:
Most of the users are male in gender,middleaged in age group and subscribers in user type.Overall it has been found that a large section of users are middle-aged men who are subscribers followed by young men who are subscribers. Though the number of subscribers are more the median duration taken by subscribers are less than the customers.Most of the users don't drop the bikes at the same station as to where they start irrespective of their gender, user type and age group. Meanwhile the median and mean duration of users whose end station and start station are same is higher than the duration of users where both the stations are not the same. This can be attributed to the presence of many outliers. There is no correlation between the frequency and duration taken when it come to where the bike is dropped. Age and duration taken has a negative correlation and most of the users are particularly between the age of 30-38 who take within 10000 secs.

## Explanatory analysis:
A frequency distribution showing the correlation and comparison of all categorical variables are plotted. boxplot and violinplot is showed for the categorical variables that is found to have unexpected median in duration.The correlation of two quantitative variables i.e age and duration is also showed using heatmap. 
