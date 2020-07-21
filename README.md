# Movies-Recommender-System
Implementation of different filters to recommend a movie to a user.

## Overview
These filters are used to predict the rating or preference that a user would give to an item.

## Technologies Used
### Python3 Libraries
```bash
pandas,numpy,scikit-learn,pip3
```
## Explanation of Filtering Methods
There are basically three types of Recommender Systems -
### 1. Demographic Filtering
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This method generalizes recommenders for every user, based on movie popularity or genres. Basic idea behind this approach is that movies with higher popularity have a higher probability to be liked by the average audience.But this recommender filter provides a general chart of recommended movies for all the users. This is not based on the preference and taste of a particular user. So we move on to a better recommender i.e. Content Based Filtering.

### 2. Content Based Filtering
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This suggests similar items based on a given item. This method used the metadata, such as genres, director, actors etc. The basic idea behind this approach is, if a person likes a particular item, he/she will also like the items similar to it.

### 3. Collaborative Filtering
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This method matches the users and suggests the movies to a user that is liked by the other similar users or recommends the movies based on the past preferences.

