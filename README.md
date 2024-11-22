# Movie Recommendation System

In this project I created three categories of filtering systems for movies.

First was popularity based system, which simply involved data manipulation and mathematical equations to get the highest average rated movies.

Next was Collaborative filtering, which using scikit learn's surprise module applies singular value decomposition algorithm to predict what different users would rate different movies, based on their past ratings.

Finally, I built a content-based filtering system that analyzed the description of each movie and based on that returned a list of similar movies using Term frequency Inverse Document Matrix to create a linear similar matrix.

This project was built on jupyter notebook