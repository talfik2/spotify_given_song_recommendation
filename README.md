# spotify_given_song_recommendation

In this repository, I built recommendation system for given 42305 Spotify songs based on their genre, mode, and duration.

I used `sklearn.decomposition`' s NMF to did that,

and I preprocessed the data by `normalize` method of `sklearn.preprocessing`

I also replaced Na values with `sklearn.impute`s `SimpleImputer`

The source of data is: https://www.kaggle.com/mrmorj/dataset-of-songs-in-spotify

It is indeed a regression algorithm because this model involves ranking entities and returning the highest ranked ones (in order) to the user. For more info, check out user- centered linear regression from : https://towardsdatascience.com/introduction-to-recommender-systems-6c66cf15ada#:~:text=In%20content%20based%20methods%2C%20the,a%20user%20to%20an%20item
