# Movie Recommender Backend

This repository contains the code for the flask which is the backend for [MOVIEMANIA - movie recommendation tool](http://succinct-foot.surge.sh/#/) whose frontend repository is [movie-recommendaer-fe](https://github.com/deepti-29/movie-recommendation-fe/tree/master).

It is a simple, single API backend made using flask with python. The API takes two input params, inpur string and N (the count of recommendations required) and in reponse gernerates a list of N movies which are most similar to the movie name which is closest to the given input string. For these recommendations, it utilises a preprocessed matrix of movie data and a pretrained machine learning model using kNN algorithm. You can find the jupyter notebook used for training the model also inside this repository. This backend is deployed on heroku (https://piplup-mew.herokuapp.com/movie/good?count=6).

The code is in the master branch not in the main branch.
