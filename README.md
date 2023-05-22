# Capstone-Project-Netflix-Movies-and-TV-Shows-Clustering

AlmaBetter Capstone Project  - Unsupervised: Netflix Movies And Tv Shows Clustering.

Project Status: Completed (100/100)


Netflix Inc. is an American media company based in Los Gatos, California. Founded in 1997 by Reed Hastings and Marc Randolph in Scotts Valley, California, it operates the over-the-top subscription video on-demand service Netflix brand, which includes original films and television series commissioned or acquired by the company, and third-party content licensed from other distributors. (Wikipedia)


This dataset consists of tv shows and movies available on Netflix. The dataset is collected from Flexible which is a third-party Netflix search engine. Netflix movies and TV shows clustering is a data analysis and machine learning technique that Netflix uses to group its content into similar categories. This technique involves analyzing the various characteristics of each title, such as genre, cast, and plot, and using algorithms to identify patterns and similarities. In essence, it's a set of algorithms using machine learning to analyze user data and movie ratings. To make it more effective, Netflix has set up 1,300 recommendation clusters based on users viewing preferences. Netflix's target market is young, tech-savvy users and anyone with digital connectivity. The audience of Netflix is from diverse age groups and demographics. However, most of the audience are teenagers, college-goers, entrepreneurs, working professionals, etc. Netflix's target consumers are divided into segments based on demographics, behavioural intents, and psychographic segmentation. Like most licensing agreements, the deal is structured in a traditional form, whereby Netflix pays for each film determined by rate cards on a sliding scale by each title's domestic or worldwide box office receipts. Netflix uses machine learning and algorithms to help break viewers' preconceived notions and find shows that they might not have initially chosen. To do this, it looks at nuanced threads within the content, rather than relying on broad genres to make its predictions.




![image](https://github.com/samchak18/Capstone-Project-4_Netflix-Movies-and-TV-Shows-Clustering/assets/114379464/313f5668-b90d-4fab-b32e-cec44a7790f8)




Generally, movie recommendation systems cluster the users in a finite number of similar groups based on their previous activities and profile. Then, at a fundamental level, people in the same cluster are made similar recommendations. Netflix developed a new machine learning algorithm based on reinforcement learning to create an optimal list of recommendations considering a finite time budget for the user. Here are 7 examples of clustering algorithms in action.
- Identifying Fake News. Fake news is not a new phenomenon, but it is one that is becoming prolific. 
- Spam filter.
- Marketing and Sales. 
- Classifying network traffic.
- Identifying fraudulent or criminal activity. 
- Document analysis. 
- Fantasy Football and Sports.



Project Summary :

Problem Statement :

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

About the Data :

We have the data of which contains details of customers like id , age, gender and also contains the details of the customers vehicle

Dataset info:


Number of records: 7787

Number of features: 12

Features information:

The dataset contains features like:


show_id : Unique ID for every Movie / Tv Show

type : A Movie or TV Show

title : Title of the Movie / Tv Shows

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Release year of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Generes

description: The Summary description

Project Work flow:

- Importing Libraries,
- Loading the dataset,
- Data Summary,
- Data Cleaning & Data Analysis,
- Feature selection,
- Implementing different clustering methods,
- Conclusion,
- Future Work.




![image](https://github.com/samchak18/Capstone-Project-4_Netflix-Movies-and-TV-Shows-Clustering/assets/114379464/8eb63ae3-09a2-40a5-93eb-f692c933e181)




Conclusion:

- Director and cast contains a large number of null values so we will drop these 2 columns .
- In this data-set there are two types of contents where 30.86% includes TV shows and the remaining 69.14%  carries Movies.
- We have reached a conclusion from our analysis from the content added over years that Netflix is focusing
movies and TV shows (From 2016 data we get to know that Movies is increased by 80% and TV shows is  increased by 73% compare)
- From the data-set insights we can conclude that the most number of TV Shows released in 2017 and for  Movies it is 2020
- On Netflix USA has the largest number of contents. And most of the countries preferred to produce movies  more than TV shows.
- Most of the movies are belonging to 3 categories
- TOP 3 content categories are International movies , dramas , comedies.
- 	In text analysis (NLP) I used stop words, removed punctuation's , stemming & TF-IDF vectorizer and other  functions of NLP.
- 	Applied different clustering models like K-means, hierarchical, Agglomerative clustering, DBSCAN on data we got the best cluster arrangements.
- 	By applying different clustering algorithms to our data-set .we get the optimal number of  cluster is equal to 3
- 	From this clustering analysis we can create Netflix movies and tv shows recommendation systems & also we can use topic modelling.


References:

Wikipedia.





