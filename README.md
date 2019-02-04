# Forgobike-data-visualization
## Investigation Overview:
In this investigation, I want to look at how factors such as age group, gender, user type and whether the start station and end station are same will influence the frequency of bike rental and duration taken.

## Dataset overview:
The original dataset consists of duration,start time, end time, information about start station and end station,latitude,longitude,bike id,user type,member birth year and member gender. 

## Data Cleaning and adding columns:
The data is cleaned and columns such as age,age group and whether the start station and end station are same are added to the dataset to have a deeper analysis.Age is calculated by subtracting 2017 from member birth year.The age group is categorised as young who are less than or equal to 30,middle aged who are between 30 and 50 and old who are greater than 50.'start=end' column is included to categorize whether the start station being equal to the end station is true or false by comparing the station ids.

## Summary of steps involved
The frequency of start station and end station being equal and not equal is first found out.Then the median duration of both are compared.The correlation of the variable with other variables are also found out.The frequency of all the categorical variables like age group,gender,user type and the inter correlations are observed.How these variables affect the duration is noted down.The quantitative correlation between age and duration is highlighted. 
