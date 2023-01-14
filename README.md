# Song-recommendation-system-Spotify
An algorithm that selects the most similar songs for a selected song from the dataset provided by the spotify platform.

The project was made in order to present an algorithm that easily recommend 5 songs that are similar to the one chosen by user. 
An algorithm selects the most similar songs from the dataset provided by the spotify platform. 
Calculations are based on parameters such as tempo, energy and danceability of the track.

I used pandas for working with dataset, creating dummy variables and appending new columns. 
Recommendation system was made by calculating the distance between choosen song and rest of the songs from the dataset. For the estimation I used scipy.
