# Spotify_Playlist_Like_Predictor
In this project, machine learning models are used for predicting whether a user will like a spotify playlist based on the 
playlists liked by the user.

![Spotify_Logo](https://github.com/Palash09/Spotify_Playlist_Like_Predictor/blob/master/Spotify_Logo.png)

<b>Steps to run the 1st part of the project.</b>

There are two ways to execute this project, either through 
1. "Spotify_Playlist_Feature_Extraction_1st_Playlist.ipynb" jupyter notebook or by using "Spotify_data.py" python file.

2. If you choose the 1st way,  you'll have to pass the playlist_index of the playlist, by referring 
"playlists_like_dislike.json" file. Using this method, you'll be able to visualize different attributes of a 
single playlist and at last the results can be saved in ".csv" file.

3. The step 2 should be repeated if you want to visualize the results of each and every playlist in 
"playlists_like_dislike.json" file. This will also help you in generating the csv files for each playlist.

4. If you want to complete the process of building the dataset faster, you can opt for "spotify_data.py" python file. 
Here in this file, you only have to pass the name of the json file which consists the Uniform Resource Indicator 
information of all the playlists.

NOTE: It is highly recommended to keep the jupyter notebooks , python files and json files in the same location.

5. You can execute the "spotify_data.py" python file in the command prompt by entering the following command.

------> python spotify_data.py

NOTE: This will take some time to execute and will generate a ".csv" file for each playlist and these 
playlists will be stored in the location specified.

<b>Steps to run the 2nd part of the project.<b>
 
1. We have to load the all the ".csv" files which contains the information of the playlists.

2. These playlists songs are then classified under the categories of like and dislike.

3. These multiple playlists are then converted into a single playlist for ease of handling.

4. We will remove the unwanted columns, which can hinder the further process.

5. Exploratory Data Analysis is performed of the playlists dataset.

6. At last, Machine Learning Model is built using one of the best performing machine learning classifiers.

7. Using this Machine Learning Model, we are able to perform the prediction of songs that are liked or disliked by the users.


