# spotify_given_song_recommendation

In this repository, I built recommendation system for given 42305 Spotify songs based on their genre, mode, and duration.

I used `sklearn.decomposition`' s NMF to did that,

and I preprocessed the data by `normalize` method of `sklearn.preprocessing`

I also replaced Na values with `sklearn.impute`s `SimpleImputer`

The source of data is: https://www.kaggle.com/mrmorj/dataset-of-songs-in-spotify
