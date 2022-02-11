# Hybrid Engine Movie Recommendation System
Hybrid engine consists of Content based recommendation system, Collaborative recommendation system and Factorization.
The dataset used was from Kaggle that was collected through the MovieLens web site during a seven-month period by the GroupLens Research Project at the University of Minnesota.
This data set consists of:
* 100,000 ratings (1-5) from 943 users on 1682 movies. 
* Each user has rated at least 20 movies. 
* Simple demographic info for the users (age, gender, occupation, zip)

![EDA](https://user-images.githubusercontent.com/92283861/153573291-beae7d91-7785-47ff-baf1-8f8ad847cc59.png)

### How does hybrid engine make recommendations:
1. At the beginning, a new user would be invited to fill a form which allows them to state their movies interests catagory wise since there would not a history of the user.

2. Recommendation will be made to the user based on catagories he/she stated in step 1. (Content-Based)

![Content](https://user-images.githubusercontent.com/92283861/153574021-e9c0a392-87b3-48f3-aedb-04b8715c13b5.png)

3. When the user as well as other new users start to watch a number of movies, the Collaborative Filtering System (both Item-Based and User-Based) will be activated to recommend movies to users. 

![Item](https://user-images.githubusercontent.com/92283861/153574094-b1b3bd59-f417-4889-a763-2e9c63d70d3a.png)
![User](https://user-images.githubusercontent.com/92283861/153574099-75954473-d381-4078-83b6-b5609fb8112b.png)

4. With factorization the engine can calculate the potential ratings that the user would have given to movies he/she has not watched, and recommend to the user movies that he/she might be interested but has not watched.

![Factorization](https://user-images.githubusercontent.com/92283861/153574110-5e7454e2-12a3-4e21-8e08-9927e983db32.png)
