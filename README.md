# spotify_given_song_recommendation

In this repository, I built recommendation system for given 42305 Spotify songs based on their genre, mode, and duration.

I used `sklearn.decomposition`' s NMF to did that,

and I preprocessed the data by `normalize` method of `sklearn.preprocessing`

I also replaced Na values with `sklearn.impute`s `SimpleImputer`

The source of data is: https://www.kaggle.com/mrmorj/dataset-of-songs-in-spotify

It is indeed a **unsupervised learning regression algorithm** because: 
- NMF as an Unsupervised Technique: Non-Negative Matrix Factorization (NMF) is primarily an unsupervised learning technique. It's used for dimensionality reduction and feature extraction without the need for labeled data.
        - Ref: The original paper introducing Non-Negative Matrix Factorization by Daniel D. Lee and H. Sebastian Seung (2001) presents NMF as an unsupervised learning technique for dimensionality reduction and feature extraction: Nature article.
Many machine learning textbooks, such as "Pattern Recognition and Machine Learning" by Christopher M. Bishop, categorize NMF under unsupervised learning techniques.

- Recommendation System: Creating a recommendation system involves finding patterns in the data to suggest items (in this case, music) to users based on their preferences or behavior. This is often done using unsupervised techniques like clustering or matrix factorization.
        - Ref: Recommendation systems are often categorized as unsupervised learning tasks in literature. For instance, in the book "Recommender Systems Handbook" edited by Francesco Ricci et al., Chapter 2 discusses recommendation system concepts within the context of unsupervised learning.
Research papers on recommendation systems often describe the use of unsupervised techniques such as clustering or matrix factorization for generating recommendations without explicit supervision signals.

- User Input Consideration: While the inclusion of user input tracks adds a personalized aspect to the recommendation, it doesn't change the fundamental nature of the task as unsupervised learning. The recommendation system still relies on patterns and similarities in the data to make suggestions, rather than explicit labels or target outputs.
        - Integration of NMF in Recommendation Systems: Numerous research papers and articles demonstrate the use of NMF in recommendation systems without explicit supervision. For example, the paper "Non-negative Matrix Factorization Techniques for Recommender Systems" by Chi Wang et al. (2014) explores the application of NMF in recommendation systems without requiring labeled data: ResearchGate article.
