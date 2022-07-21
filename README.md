# ETL Movie Data

## Summary

This project was to take combine the data in 3 different source files (a .json file, and 2 .csv files)  using Extract, Transform, Load (ETL) methodology and ultimately end up with a database of usable movie data. Functions were written to remove duplicate columns, combine alternate titles, drop nulls, use regex to compile budget data, runtime and release date. The data was imported into an SQL database in postgres. The queries below show the database ended up including data for 6052 movies and 26,024,289 ratings.

![movies_query.PNG](https://github.com/mcwatts88/ETL_Movie_Data/blob/main/Resources/movies_query.PNG)

![ratings_query.PNG](https://github.com/mcwatts88/ETL_Movie_Data/blob/main/Resources/ratings_query.PNG)
