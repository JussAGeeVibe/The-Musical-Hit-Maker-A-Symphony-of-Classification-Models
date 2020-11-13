# capstone_2 : The Hit Maker
ML (Machine Learning) Capstone

•	Data set used will be The Spotify Hit Predictor Dataset (1960 - 2019).
•	Dataset contains 41,106 rows with 19 columns of categorical and continuous data.

I sought to build a classification algorithm that could predict a hit song based on the various categorical and continuous features of the song.
I cleaned the data by eliminating what I believed to be useless columns.
Scaled the data before splitting into training and testing sets.
Ran seven different classifiers with varying parameters before picking two for fine tune. Went from fine tuning two algos to hypertuning the best of the fine tuned algos. 

Used Pandas, MatPlotLib, Seaborn, SKLearn, Numpy, and various other Python packages. 

Included is a PowerPoint presentation of my findings. 

Based on how I cleaned my data I found that instrumentalness (a measure of spoken word or singing) had the highest correlation. The key of the song played the smallest role but songs writting in a major scale as opposed to a minor scale had a higher correlation. My algorithm also found that danceability played an important role in determining the likelihood of being a hit. 

Someone could potentially train a computer to compose music and based on these findings could potentially train it to only produce hits. 
