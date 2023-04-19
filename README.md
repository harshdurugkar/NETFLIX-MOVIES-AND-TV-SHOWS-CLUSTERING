# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING
![Annotation 2022-10-20 174121](https://user-images.githubusercontent.com/76514358/196945045-6feed2bd-567b-43b5-9635-617b842e947d.png)
Introduction :-
1) From 2006 Netflix start the analysing user data to predict how much a viewer would like a movie,  based on previous user Preferences.

2) Whenever we access the Netflix service, Netflix recommendations system strives to help us to find a show or movie to enjoy with minimal effort.

3) All of these done by  using user data as an inputs that we process in our algorithms.  ( An algorithm is a process or set of rules followed in a problem solving operation ) 

4) As well as we use clustering in this project. Clustering is a method of unsupervised learning and is a common technique for statistical data analysis used in many fields. 

Problem Statement :- 
1) This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search  engine.

2) In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s  number of movies has decreased by more than 2,000 titles since 2010, while  its number of TV shows has nearly tripled. It will be interesting to explore what  all other insights can be obtained from the same dataset.

3) While using this Netflix Data we Try to Understand :- 
     i) Understanding what type content is available in different countries.
     ii) Is Netflix has increasingly focusing on TV rather than movies in recent years.
     iii) Clustering similar content by matching text-based features.
     
     
Work of Flow :- 
 In workflow we first collect and understand the data. While understanding the data we found there are 7787 rows and 12 numbers of columns. Then we find if any data miss or not in the dataset. If any Data is missed we try to fix it. Then we start to perform exploratory data analysis(EDA). After analysis we move on to our Machine Learning Part where we Perform Text Processing, DBSCAN, K-means Clustering, Hierarchical Clustering and last we move on to our conclusion.


Data Review :
1)  The shape of dataset is (7787 x 12)
2) Total Number of Rows are : 7787
3) Total Number of Columns are : 12
4) Missing Value in Column Wise :- 
     i) director  - 2389
    ii) cast  -  718
   iii) country  -  507
    iv) date_added  -  10
     v) rating  -  7
5) The Total number of duplicate values in the data set is = 0


Conclusion :- 
1) After Visualize Total Release Movies/Tv shows in Last 10 years, we find out :- 
        i) 2018 is a year where the Maximum number of movies have been released which is Total 1121. 
       ii) 2017 is a Second Highest year For Maximum number of movies have been released which is Total 1012.
      iii) 2019 is the Third Highest year where 996 number of movies have been released.
2)  69% are Movie type of Contents on Netflix which is Total 5377 Number of Movies.  31% are TV Show type of Contents on Netflix which is Total 2410 Number of TV Shows.
3)  i) The United State is a Country which produces the Highest Number of Movies/Shows on Netflix. Total Number of  Movies/Shows produced in the US is 3296.
      ii) India is a Second Highest Country which produces Highest Number of Movies/Shows on Netflix. Total Number of Movies/Shows produced by India is 990.
      iii) The United Kingdom is the Third Highest Country which produces the Highest Number of Movies/Shows on Netflix. Total Number of Movies/Shows produced by the UK is 722.
4)  i) Tv-MA is a Highest Rating Distribution For Movies and Shows on Netflix, which is Total 2863.
      ii) Tv-14 is the Second Highest Rating Distribution For Movies and Shows on Netflix, which is Total 1931.
      iii) Tv-PG is the Third Highest Rating Distribution For Movies and Shows on Netflix, which is Total 806.
5)    i) Drama is a Top Genres For Movies/TV Shows on Netflix. That is, the content of the movie in the drama  
           genre has been produced the most, which is 2810 Times.
       ii)  Comedy is the Second Highest Genre For Movies/TV Shows on Netflix which is 2377 Times.
      iii)  Documentary is the Third Highest Genres For Movies/TV Shows on Netflix which is 1139 Times.
      iv)  Action_Adventure are in 4th Position & Romance are in 5th Position.
6)  i)  Jan Suter is the top director in the Netflix industry & he has Directed 21 Movies/Shows.
      ii)  Raul Compose is the Second top director in the Netflix industry & he has Directed 19 Movies/Shows.
     iii)  Marcus Raboy is the Third top director in the Netflix industry & he has Directed 16 Movies/Shows.
      iv)  Jay Karas is the 4th position & he has Directed 15 Movies/Shows and Cathy Garcia-Molina is the 5th Position & he has Directed 13 Movies/Shows.
7)  i) Anupam Kher is the Top Cast on Netflix As Our Visualization.
     ii) Shah Rukh Khan is the second highest cast on Netflix.
    iii) Naseeruddin Shah is the third highest cast on Netflix.
    iv) Om Puri is the 4th Highest cast on Netflix.
     v) Akshay Kumar is the 5th Highest cast on Netflix.
8 )   Most of the movies on Netflix have a duration range from 85 to 115 minutes.
9 )   Most TV shows on Netflix have a length of 1 season only.
10)  i) Drama is the most produced genre in a lot of Non-English speaking countries.
       ii) Comedy is the most produced genre in English speaking countries like the United States of America and the United Kingdom and Canada.
      iii) Drama and Comedy are the most produced genres in the top countries with exceptions of Japan and South Korea.
      iv) Japan is the biggest producer of Anime. Anime is also the most produced genre in Japan.
       v) Most South Korean content is from the Romance genre.
      vi) Documentaries are mainly produced in the United Kingdom and United States of America.
11)  i) The above graph depicts seasons of TV shows signed vs the movies signed.
      ii) This distinction gives contacts as TV shows require recurring investment for each season. So the TV  numbers have been increased in accordance to the seasons. As they were considered as one entity earlier. 
     iii) We can observe that TV shows signed have been higher than movies in 2016. While the movies signed have been higher, it is blatantly visible that the TV shows signed per year is catching up to the   movies signed by the year.
12 )   After Performing DBSCAN cluster the data into 10 clusters with a silhouette score is 0.43875.
13 )   After Performing K-means Clustering  the elbow and optimal silhouette score were found at 8 clusters  with a silhouette score of 0.474, Davies-Bouldin Index of 0.884 and Calinski-Harbaz Score of 2932.28.
14)    After Performing Hierarchical Clustering the dendrogram distance was optimal at a distance of 20 with eight clusters producing a silhouette score of 0.4705, Davies-Bouldin Index of 0.8839 and Calinski- Harbaz Score of 2930.84


References-

1) Clustering in Machine Learning By GeekforGeeks.
2) k-means Clustering in machine learning From TowardsDataScience By Team Education Ecosystem(LEDU).
3) DBSCAN Clustering Algorithm for Machine Learning From Analytics Vidhya By Abhishek Sharma.
4) Hierarchical Clustering in Machine Learning From JavaPoint .
5) Text Processing From Datarobot.



