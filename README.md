# Model-Based-Movie-Recommendation-System

## Purpose:
This Notebook Recommends Movies by finding correlation based on user rating of each movie<br />

## Correlation:
Customer A likes restaurants 1 and 2. <br />
Customer B like restaurant 2 so he's most probable to like restaurant 1 too.<br />

## Data:
1-We have a ratings data which contains ratings given to different movies by different users.<br />
2-We have a movies data which contains names and IDs of movies.<br />

## Libraries Used:
1-Pandas<br />
2-Numpy<br />
3-SKlearn<br />

## Approach
1-The Data contains rating of different movies given by different Users.<br />
2-Then we will group the data by movie IDs and find the count of ratings received by each movie<br />
3-Then we will create a pivot table.<br />
4-It will take users as rows and movies as columns<br />
5-The cell will be filled by the rating they give to a movie they watched<br />
6-Null values will be filled by 0
7-There are 943 users<br />
8-we will compress the data to have 1664 * 943 to 1664*12<br />
9-Then we will find correlation of every movie with each other based on user ID<br />
10-If a person rated starwars high, he's likely to enjoy the movies that have high correlation with starwars.<br />

