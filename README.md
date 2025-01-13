# Song Popularity Prediction on Spotify Dataset
This repository contains the source code for a simple project aimed at predicting song popularity using Spotify data. The focus is on numerical features such as energy, tempo, and danceability.

## Dataset
The dataset used in this study is sourced from [Kaggle](https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset/data). It contains a total of 4,381 songs, including both popular (high popularity) and less popular (low popularity) tracks.

## Methods
The project explored features like energy, tempo, danceability, loudness, and valence to predict song popularity.
- Preprocessing steps included removing irrelevant columns, encoding categorical features (genre and subgenre), and handling missing values by dropping incomplete rows.
- A correlation analysis was performed to select features with a stronger relationship to popularity.
- The Random Forest Classifier was used for its ability to handle various data types and provide stable predictions. The model was evaluated using metrics like R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

## Results
The model performed reasonably well, with an average R-squared of 0.95 during testing and consistent cross-validation results. The low error values suggest the model was able to capture useful patterns in the data.






