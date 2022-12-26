# Content-based-Movie-Recommendation-System
A content-based recommender system that recommends movies similar to the movie the user.

## Overview
The movies are recommended based on the content of the movie you entered or selected. The main parameters that are considered for the recommendations are the genre, director, and top 3 casts. The details of the movies, such as title, genre, runtime, rating, poster, casts, etc., are fetched from TMDB. 

## Get API Key From TMDb
Create an account in https://www.themoviedb.org/. Once you successfully created an account, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for an API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request has been approved.

## Run the Project
1. Clone or download this repository to your local machine.
2. Install all required libraries after thoroughly reading the code
3. Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)
4. Replace YOUR_API_KEY in both the places (line no. 15 and 29) of static/recommend.js file and hit save.
5. Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.
6. Go to your browser and type http://127.0.0.1:5000/ in the address bar.
7. Yay! That's it.

## Datasets
sources of datasets

1. IMDB 5000 Movie dataset - https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset
2. The movie datset -https://www.kaggle.com/rounakbanik/the-movies-dataset
3. List of movies in2018 - https://en.wikipedia.org/wiki/List_of_American_films_of_2018
4. List of movies in2019 - https://en.wikipedia.org/wiki/List_of_American_films_of_2019
5. List of movies in 2020 - https://en.wikipedia.org/wiki/List_of_American_films_of_2020
6. List of movies in2021 - https://en.wikipedia.org/wiki/List_of_American_films_of_2021
7. Lis of movies in 2022 - https://en.wikipedia.org/wiki/List_of_American_films_of_2022

(Download movies_metadata.csv and credits.csv from Kaggle)
