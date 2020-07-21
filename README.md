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
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This method generalized recommenders for every user, based on movie popularity or genres. Basic idea behind this approach is, movies with higher popularity are having a higher probability to be liked by the average audience.

### 2. Content Based Filtering
This suggests similar items based on a given item. This method used the metadata, such as genres, director, actors etc. The basic idea behind this approach is, if a person like a particular item, he/she will also like the items similar to it.

### 3. Collaborative Filtering
This method matches the users and suggest the movies to a user that are liked by the other similar users or recommend the movies based on the part preferences.
