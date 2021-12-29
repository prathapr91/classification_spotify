## **Predicting Hit Songs using Machine Learning Classification**

 

**Background**

Having a hit song can make an artists career and make millions for record labels. While hit songs have certain tropes, such as upbeat and catchy, not all songs that fit this bill go viral. The goal of this project is to use machine learning classification to predict whether a song will be a hit depending on its audio characteristics. With a data-driven approach to evaluating a song, record labels and artists will be better equipped in their music production moving forward.



 **Data Description**

- My target variable is a binary indicator of whether or not a song is a hit. A given song is determined a hit song if it appeared on either the billboard 100 or spotify top 100 list at any point in time.
- My independent variables are the following:
  - Duration of the track in milliseconds
  - Energy, ranging from 0 to 1.0, which measures intensity and activity
  - Key, the key the track is in. Integers map to pitches using standard Pitch Class notation . E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on.
  - Mode, the modality (minor or major) of a track. Major is 1 and minor is 0
  - Time signature, which measures how many beats are in each bar
  - Acousticness, ranging from 0 to 1.0, which measures how acoustic the track is
  - Danceability, ranging from 0 to 1.0, which describes how suitable a track is for dancing
  - Instrumentalness, ranging from 0 to 1.0, where values closer to 0 are more vocal and values closer to 1.0 are more instrumental. For example, rap music will typically be on the lower end of the scale while classical music will typically be on the higher end of the scale.
  - Liveness, which detects the presence of an audience in the recording
  - Loudness, which detects the overall loudness of a track in decibels
  - Speechiness, ranging from 0 to 1.0, which detects the presence of spoken words in a track. Values closer to 1.0 are more spoken than music (I.e. a talk show), whereas values closer to 0 contain little speech and is mostly music.
  - Valence, ranging from 0 to 1.0, which detects the happy and cheerful emotions in a track
  - Tempo, measured in beats per minute
- I am envisioning a unit of my analysis to be a classification metric of the model. Given the costs associated with producing and marketing music, it is very important that there are few false positives. That being said, it is also important to not miss out on a golden opportunity, making precision important as well. For this reason, I will use F1 as this incorprates both precision and recall for a more holistic look at model performance.



**Data Sources**

This [Kaggle Dataset](https://www.kaggle.com/multispiros/34740-hit-and-nonhit-songs-spotify-features) contains data on over 34,000 songs extracted from Spotify

Further information on the fields can be found [here](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features)

 

**Tools**

- Pandas, Numpy, and Scikit-learn for data analysis, manipulation, and statistical analysis
- Matplotlib and Seaborn for data visualization



**Work Location**

- [High level summary of my analysis](https://github.com/prathapr91/classification_spotify/blob/main/Classification_Deck.pdf)
- [Detailed writeup of methodology and analysis](https://github.com/prathapr91/classification_spotify/blob/main/Class_Writeup.md)
- [Underlying coding used for analysis](https://github.com/prathapr91/classification_spotify/blob/main/Class_final.ipynb)

