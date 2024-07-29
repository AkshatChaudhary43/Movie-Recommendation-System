# Movie Recommender System
A movie recommender system suggests movies to users based on their preferences, behavior, or similarities to other movies.<br><br>
For my project I have used Content-Based Filtering:<br>
Basically this filtering recommends movies based on the attributes of the movies themselves and the user's past preferences. For example, if a user likes action movies, the system will suggest other action movies by analyzing movie genres, actors, and directors.

<h4>Key Components</h4>
<ol><li>Item Profiles:</li>
Information about the movies, such as genres, directors, actors, and plot summaries.<br>
<li>Similarity Measures:</li>
Algorithms to compute similarities between users or items. This Project includes cosine similarity.<br>
<li>Recommendation Algorithms:</li>
Used Vectorization, Stemming and pickling.<br>
</ol>

<h4>Libraries and Tools</h4>
Python Libraries: scikit-learn, pickle, pandas, requests<br>
Data Sources: kaggle, Movie databases like IMDb, The Movie Database (TMDb), or user-generated datasets like MovieLens

<h5>Note:</h5>
Need to create pkl file for movie and similarity to use in app.py and provide the right path.
