# Introduction
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office.

**Problem Statement:** You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## Main Objective
 Find the type of films that are currently doing better in box office and use the data to help create a new movie studio

## Other Objective
* Find movies with lowest number of votes and highest number of votes
* Find movies with highest number of votes
* Find maximum movies that are bought locally and internationally

## Data Understanding
 The dataset used for this anaysis was downloaded from different box offices. The data was was acquired from Box Office MojoLinks, IMDB, Rotten Tomatoes, TheMovieDB, The Numbers. The data contains information about movies that have posted in box offices. The data has two files: idmb movie ratings and basics and boom movies gross .The whole combined data has 2447 rows and 12 columns.The data has the following set of information about movie:
*  movie_id: This is the primary key used to identifies all movies
* primary_title: This is the original movie title the movie was given
* start_year: This is the year the movie started production
* runtime_minutes: This is the count of minutes in each movie  
* genres: This is the the classification of the movie
* averagerating: This is the rating collected over the continent from viewers
* numvotes: This is the number of people who voted the movies and their  count was used to generate ratings
* title: This is the title the movie was produced with
* studio: This is the studio in which each movie was produced
* domestic_gross: This is the amount of money collected from each sell of movies in the country of origin 
* foreign_gross:    This is the amount of money collected from each sell of movies in the country of origin
*year: This is the year the movie was produced

## Data Preparation
Before analyzing the data had to be processed and cleaned. The data was checked for null values and also duplicates. This data had a few columns tha had missing or null valuesand we had to delete the rows to preserve the important information. Some Exploratory Data Analysis(EDA) was done to the data to determine if there was any patterns in the data. This data had one categorical column, meaning that these columns had to be converted to numeric features in order to be used in evaluation. The categorical columns was then changed from object to float. This data was then ready for evaluation.

### genres number of votes above 8.0 ratings
![genretotal](https://user-images.githubusercontent.com/79564088/203026173-85214ff5-4440-4c89-8cd2-005db0d08551.PNG)


### title number of votes above 8.0 rating

![titlevotes](https://user-images.githubusercontent.com/79564088/203025905-4f8c7d57-0ebf-4b94-a26e-2f0ae727b930.PNG)

## Conclution
* Interception is the highest watched movie and was acted on 2010
* Bohemian Rhapsody is the highest selling movie internationaly
* Avengers infinity is the was highest selling movie locally
* The best genre of movie that is liked by a alot of people in general is an  action, adventure, scifi movie
* Action, thriller genres are highly watched movies 
* Biography, Drama, Music is the most selling genre internationally

## 8. Recommendation
I would recommend that the managers should produce movies that relate with  combination of:
 
* The studio should Adventure, animation, comedy movies , action, thriller movies and biography, drama and music genres for foreign countries because the have the highest selling rates in foreign countries
*  Action, adventure scifi movies has the highest number of people watching it locally and and in foreign countries thus should be given a priority 
* Adventure,drama,scifi movies, action thriller and western drama are the highest watched genres 






## Repository Guide
CSV Files:
The data set used can be found [here](https://github.com/K-made/phase1/blob/main/bom.movie_gross.csv)

sql Files:
The data set used can be found [here](https://github.com/K-made/phase1/blob/main/im.db.zip)

Notebooks: The notebook can be found [here](https://github.com/K-made/phase1/blob/main/student.ipynb)

Presentation: The Presentation can be found [here](https://github.com/K-made/phase1/blob/main/bfsdf.pdf)



