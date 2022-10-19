# Movie-Recommendation-Engine
Recommendation systems are becoming increasingly important in today’s extremely busy world. People are always short on time with the myriad tasks they need to accomplish in the limited 24 hours. Therefore, the recommendation systems are important as they help them make the right choices, without having to expend their cognitive resources.
<br>

These systems estimate the most likely product that  consumers will buy and that they will be interested  in. Netflix, Amazon, and other companies use  recommender systems to help their users find the  right product or movie for them.

<h2>Types of Recommendation Engines </h2>
<ul>
<li><b>Demographic Filtering:</b>The recommendations are the same for every  user. They are generalised, not personalised. These types of systems  are behind sections like “Top Trending”.</li>
<li><b>Content-based Filtering:</b>These suggest recommendations based on  the item metadata (movie, product, song, etc). Here, the main idea  is if a user likes an item, then the user will also like items similar to it.</li>
<li><b>Collaboration-based Filtering:</b>These systems make  recommendations by grouping the users with similar interests. For  this system, metadata of the item is not required.</li>
</ul>

<h2>Contents of Datasets</h2>
<ul>
<li><b>Movies Dataset:</b> This dataset files contains contains all  the metadata information about the movie.</li>
<li><b>Credits Dataset: </b> This Dataset file contains the  information like name and id of the movie, budget,  languages in the movie that has been released, etc.</li>
</ul>

<h2>Steps in Making the Engine</h2>
<ul>
<li><b>Perform Exploratory Data Analysis (EDA) on the  data.</b>
Exploratory Data Analysis (EDA) is an approach to analyse the data using visual techniques. It is used to discover trends, patterns, or to check assumptions with the help of statistical summary and graphical representations. 
This forms the basis of the major part in where the engine is trained and made well versed with the dataset. 

<li><b>Build the recommendation system</b>
In this step of development, the recommendation engine is further improved to make its recommendation very precise. 
</li>

<li>
<b>Get recommendations</b>
This is where this piece of code becomes into an actual working recommendation engine. 
</li>
</ul>

<h1>Output 👇</h1>
<img width="566" alt="Screenshot 2022-10-17 at 00 45 35" src="https://user-images.githubusercontent.com/51440734/196053703-e70c0443-c8b3-49c3-99cf-f7651b55c4eb.png">

<h4>All development stages for this repository are completed!</h4>

<h2>Snippet for Getting Recommendations</h2>

```
  print("Recommendations for Interstellar") <br>
  print(get_recommendations("Interstellar", cosine_sim2)) <br>
  print() <br>
```

<h2>All development stages for this repository are completed!</h2>
