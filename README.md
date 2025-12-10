I created this project in order to view my listenining statistics and visualise meaninful information regarding my Spotify usage, 
without having to provide my information to third parties. The statistics and insights provided by Spotify only go as far back as 2023 but I wanted to display the stats that incorporated the data from when I first starting using Spotify in 2018.

<img width="500" height="200" alt="Spotify_Full_Logo_RGB_Green" src="https://github.com/user-attachments/assets/e2fa3e06-00e8-4da3-a73b-755d77f45567" />

image source: https://developer.spotify.com/documentation/design#using-our-logo

I have written the code such that it can be reused with minor modifications. I will update it at a later point to make it completely reusable.

Currently, this notebook does the following:
  
1. Reads in all the .json files and saves the data in a dataframe
2. Cleans the resulting the dataframe by identifying and removing duplicated and missing values
3. Extracts additional information for all the songs in the dataframe through the Spotify API
4. Provides insights on listening behaviour on a monthly and yearly basis, as well as since Spotify was first used by the user
5. Presents visualisations of monthly listening trends, trends for different artists, changes in listening on a yearly basis, and the user's top tracks of all time
6. Highlights the top songs played by the user for any artist


As for next steps, I plan on identifying relationships between the changes in playtime of artists and the latest release of the artists music, and to identify the favourite 
genres of the user (currently, Spotify has deprecated the retrieval of genre information through their API).
  
