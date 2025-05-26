# Movie-Recommendation-Using-Collaborative-Filtering
# Introduction

At this moment, people are immersed in so many movies from different platforms online. Despite many film lovers wanting to see new stories that appeal to them, finding shows and movies to match what they like can often seem like a huge hurdle. Because there is so much to watch, users regularly find it difficult to decide what to enjoy next.We rely on recommendation systems to minimize error as much as feasible.
This problem is addressed by recommendation systems which determine what content users should see based on their past actions, likes and interactions. They do more than improve user experience; they also increase engagement using custom content.

There are different types of recommendation techniques.

A number of filtering methods are used in creating recommender systems.

# 1. Content-Based Filtering

1)Puts forth recommendations for items that are much like ones the user liked before.

2)The process includes looking at features of the items, for example, their genre, director and cast.

3)A person who likes action movies will be given suggestions for action films.

# 2. Collaborative Filtering

1)Suggests products according to the preferences of users who are similar.

2)No need for knowing what’s inside each item—system observes behaviors between users and items.

3)For example, if User A and User B like the same kinds of movies, movies that liked by User B may be advised to User A.

# 3. Hybrid Methods

1)Both content-based technology and collaborative filtering methods are used.

2)Strives to overcome typical challenges found in each method (e.g., cold start problem).

3)An example is Netflix which recommends programs using both machine learning and people working together.

# Real-World Applications

Netflix makes recommendations by understanding what you watch and comparing it to other users who act similarly.

Amazon Prime Video: Suggests content to you using suggestions from what you’ve watched and what’s popular among members.

YouTube: Shows you videos based on what your peers watch along with the ones you’ve seen.

Spotify : Discover Weekly and Daily Mix playlists are built by showing you music that people with similar interests are listening to.

# Datasets Used

This project takes advantage of these two datasets:

1)movies.csv, you’ll find information about movies using IDs, titles and lists of genres.

2)ratings.csv includes ratings given by users to several movies, along with user ID, movie ID, score given and a timestamp.

Data from the datasets are used to form the user-item interaction matrix that is important for collaborative filtering.


# What Is This Project?

The engine is built by applying Collaborative Filtering in this project. The system can suggest undiscovered titles for a user by understanding what others like who are similar to them have enjoyed—even if the user hasn't interacted with those movies before.

# Why use Collaborative Filtering?

Collaborative filtering stands out because

1)Analyses user-item relationships in detail, even without access to direct content information.

2)Gets better as it receives and reviews additional user data.

3)Finds out what is the same across all users, hidden within their actions.

4)For personalized and scalable suggestion, this project uses collaborative filtering that relies on the knowledge of similar users in the population to make recommendations.
