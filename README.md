# Project4

Goal: Create a Tableau dashboard where users can filter between songs and display audio clusters related to Acousticness, Liveness, and Tempo 

Step 1: Import dependencies and Spotify API Credentials (The user will need to set up a Spotify Developer account and follow the steps on Spotify to obtain a Client ID & Client Secret. Link: https://developer.spotify.com)

Step 2: Use the Spotify API to get a token 

Step 3: Pull a song id from Spotify 

Step 4: Define you your track recommendation and set a limit to pull "X" number of songs

Step 5: Get a json response 

Step 6: Make an empty list and run a for loop to append the the json text from the above step and pull the name of the some and artist info

Step 7: Make a data frame for the track recommendations

Step 8: Create a for loop and get the audio features for the songs

Step 9: Create a new data frame that contains the audio feautres, song name, and Spotify track id

Step 10: Get dummy variables 

Step 11: Create a new data frame that contains the song name and Spotify track id

Step 12: Using the data frame with audio feautres, song name, and Spotify track id and drop the song name, and Spotify track id because we need a clean data frame for clustering

Step 13: Do a KMeans model with a cluster number = 3 

Step 14: Fit the KMeans model to the data frame with audio features

Step 15: Add the merged_features data frame with the music_cluster you just created with the predict function

Step 16: Read in the genre csv file (This file contains a list of 48,000 songs so the songs avaialble are limited)

Step 17: Reduce the csv to only Spotify song id and genre

Step 18: Combine the merged_features data frame and the reduced csv data frame on the 'id' column and perform a left merge

Step 19: Connect to Postgres and create a table with the newly creted data frame 

Step 20: Using a Tableau Desktop account connect your to your Postgres database

Step 21: Created circle chart (based on clusters), bubble, and bar charts based on song audio features (Acousticness, Liveness, and Tempo)

Step 22: Created the dashboard page where end users can filter by song AND/OR the folowing cluster buckets: All, 0, 1, and 2




