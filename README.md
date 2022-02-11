# Hybrid Engine Movie Recommendation System
Hybrid engine consists of Content based recommendation system, Collaborative recommendation system and Factorization.
The dataset used was from Kaggle that was collected through the MovieLens web site during a seven-month period by the GroupLens Research Project at the University of Minnesota.
This data set consists of:
* 100,000 ratings (1-5) from 943 users on 1682 movies. 
* Each user has rated at least 20 movies. 
* Simple demographic info for the users (age, gender, occupation, zip)

### How does hybrid engine make recommendations:
1. At the beginning, a new user would be invited to fill a form which allows them to state their movies interests catagory wise since there would not a history of the user.
2. Recommendation will be made to the user based on catagories he/she stated in step 1. (Content-Based)
3. When the user as well as other new users start to watch a number of movies, the Collaborative Filtering System (both Item-Item and User-User) will be activated to recommend movies to users. 
4. With factorization the engine can calculate the potential ratings that the user would have given to movies he/she has not watched, and recommend to the user movies that he/she might be interested but has not watched.
