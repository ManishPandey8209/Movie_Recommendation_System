# Content_Based_Movie_Recommendation_System
CHAPTER 1 – INTRODUCTION

Recommender System works as a filter which helps the user to recommend the information based on their previous history. Recommendation systems are becoming rapidly increasingly in today’s extremely busy world. Because everyone has very less time in today’s worlds. Nobody has enough time for searching in the site and fetch the useful information. They want the information very quickly. Due to which the Recommender System come into the picture. The working of the recommender system is very easy, they just take the user previous information as an input and based on that previous information it will recommend the further information to the users. There are many types of the recommender system. In this project, we create a Content Based Movie Recommendation System. 
There are two types of the recommendation system i.e., Collaborative Recommendation system and Content Based Movie Recommendation System.

1-	Collaborative Filtering based Movie Recommendation System: - This recommender system builds a model from the user’s history and the similar decision made by the other users. This recommender will work based on the ranking giving the users to the movie and based on that it recommends the further movies to the users.

 
           Figure 1.1 – Collaborative Filtering based Movie Recommendation System
2-	Content Based Movie Recommendation System: - This recommender system work based on the data that they take from the user’s history and used this data as an input to recommend further movies to the users. It doesn’t require other users for their recommendations.

               
Figure 1.2 - Content Based Movie Recommendation

Difference b/w Content Based and Collaborative Recommendation System: -

Content Based Recommendation System	Collaborative Recommendation System
1-	Uses Properties of the items	1-	Uses the ratings from the users 
2-	Uses user’s history to find out which movie they have liked.	2-	No use of user’s history. Only another user required. 
3-	Don’t require another user for recommendation	3-	Require another user for recommendation.
Content Based Movie Recommendation System
As the development in the field of Information Technology and Internet, we are entering in the era of information overload. In this era, it is very difficult for all of us to get the information that we are looking for. And for the content provider, it is also very hard for them to make their content stand out from the crowd. This is where Content Based Recommender System comes into the picture. It helps the users to finds its valuable information and we can say it gives them what they want. This form of recommendation system uses a movie that the viewer enjoys right now as an input. The program then analyses the movie's content (storyline, genres, director, crew, and so on) to locate other films with comparable themes. The system then evaluates comparable films based on their similarity ratings and suggests the most relevant films to the viewer.

 
                                                       
                                 Figure 1.2 - Content Based Movie Recommendation

In this Project we will create a Content Based Movie Recommendation System that will help the users, find the movie. This recommender will take a movie as an input and based on that it will recommend the users what they should watch next. For making this project we use python and its some library that will help us to visualise and fetch out the movie dataset and perform some operation on that dataset to make it a valuable Dataset that we want. We used Python library such as Pandas, NumPy and many more to make our project. For making this project, we will also use some Machine Learning fundamentals like Cosine Similarity.
The main purpose of making this project is to provide user with a general understanding of how actually a Recommendation System works.
 
 Figure 1.3 - Movie Dataset

                                                                           Figure 1.3 – Columns in Dataset
1.1	Machine Learning
Machine Learning is the study of the computer algorithm that improve automatically on using data. Here, we have used Machine Learning fundamentals like Cosine Similarity. Cosine Similarity is a matrix used to measure the document Irrespective of their size and the Natural Language Processing (NLP) is a field in Machine Learning which gives the ability to the computer to understand the text and spoken words in much the same way human being can.

Cosine Similarity
We've all heard of vectors, which might be 2D, 3D, or any other dimension. Let's consider in 2D for a moment, and then go through the concept of a spot object. The projection of one vector onto the other is identical to the speck item between two vectors. The speck item in the middle of two similar arrays (i.e., with similar components) is identical to their squared module, but the dab item between them is zero if they are opposite (i.e., they don't share any headings). Furthermore, the speck item can be treated as follows for n-dimensional vectors. 
 
Figure 1.4 - Dot product formula
Speck item is vital when characterizing the comparability, as it is straightforwardly identified with it. The closeness between two vectors u and v is, indeed, the proportion between their dab item and the result of their extents.
 
 
Figure 1.5 – Formula for calculating Similarity
By applying the meaning of likeness, this will be equivalent to 1 if the two vectors are indistinguishable, and it will be 0 if the two are symmetrical or opposite. At the end of the day, the closeness is a number limited somewhere in the range of 0 and 1 that lets us know how much the two vectors are comparable.
                                      
                                                 Figure 1.6 – Cosine Similarity       


Natural Language Processing  
Regular Language Processing (NLP) is a field in Machine Learning which enables to the PC to comprehend the text and expressed words similarly person can. The value of regular language preparing has been because of the basic explanation that it can't be pretty much as exact as person. It's far from being obviously true how helpful regular language preparing can be because of the restrictions of accomplishing individual degrees of accuracy. Nonetheless, NLP discovers utility when we measure a huge arrangement of text information that it's not monetarily achievable or difficult to be handled by a human. NLP permits us to stretch out our capacity to structure elusive surveys into intellectually absorbable data. 
This is the situation inside film information. Human arrangement beats algorithmic methodologies when we unequivocally realize an audit's importance by associating it with
our own insight. Be that as it may, AI approaches make progress when preparing a huge number of motion pictures since no human has sufficient opportunity to watch them all.
CHAPTER-2 PROJECT DESCRIPTION

2.1 Purpose
The Main Purpose of making this Project is Recommender System which recommend movie to the user based on Previous watch. Basically, this recommender picks the items and based on that recommend movies to the user. This Project help the user to understand the working of the Recommender System. When we search movie in any app or in any site, this recommender will help the user and gives them a relevant result.
For ex- If we are looking for some Action movie and we have already watched some Action movies. So, this recommender picks these Action movies in our history, and it will take these pick item as an input and based on these pick items, it will recommend us further fighting movie. With the help of Recommender System our work will easier, it will automatically recommend us movies based on previous history. 

 
Figure 2.1 – Searching in Recommender System
 
Figure 2.2 – Movie-Genres Statics


           
In the fig 2.2, we can clearly see that the user watch Drama more than the other. So, the recommender system will recommend the Dramatic movies to the user. Evertime when the user open the app or any site in which he/she watched their movies, they will see the recommendation of Drama movies is more than the others, and if he/she wants to watch some Drama movie they will just use these recommendation and start watching their movie. They don’t have put more effort to search the movie and don’t ask someone and their friend which movie should I watch next. So that’s the work of recommendation system. It is basically used to  reduce the efforts of the user and gives them a basic understanding of how actually a recommender system works.




2.2 Overall system block diagram
 
Figure 2.3 – overall system block diagram
                                

The general framework block graph is displayed in figure 2.3. Tells regarding that the framework contains enormous data set of the things to be suggested. Then, at that point, the clients give some data about their inclinations to the framework. The System Combines the thing data with the client inclinations and in view of that, the framework assembles a profile of the clients. As per the data existing in the client's profile, the framework prescribes appropriate things to the client.

As we move forward, let us understand some shortcoming of the Content Based Movie Recommendation System. We all know very well it take our previous history as an input and based on that recommend us further movies. Let’s take an example, if someone watch Fighting Movie, let’s say “Warrior” and then he/she wants to watch another movie. The Recommender can help to find their interested movie. It takes user’s watched movie i.e., “Warrior” as an input and based on that it will suggest them all the related movie. “Mad Max2, Scarface, The French Connection, City Heat”, these are some movies that are related to the “Warrior”. So, the recommender system recommends these movies to the user. Even though the user’s strongly dislike all these it will suggest these moves to the user. 

