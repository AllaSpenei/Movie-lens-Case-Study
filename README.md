# Movie-lens-Case-Study  
DESCRIPTION  

Background of Problem Statement :  

The GroupLens Research Project is a research group in the Department of Computer Science and Engineering at the University of Minnesota. Members of the GroupLens Research Project are involved in many research projects related to the fields of information filtering, collaborative filtering, and recommender systems. The project is led by professors John Riedl and Joseph Konstan. The project began to explore automated collaborative filtering in 1992 but is most well known for its worldwide trial of an automated collaborative filtering system for Usenet news in 1996. Since then the project has expanded its scope to research overall information by filtering solutions, integrating into content-based methods, as well as, improving current collaborative filtering technology.  

Problem Objective : 

Perform the analysis using the Exploratory Data Analysis technique. Find features affecting the ratings of any particular movie and build a model to predict the movie ratings.  

Dataset Description :  

These files contain 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000.  

    Ratings.dat - UserID::MovieID::Rating::Timestamp  
    Users.dat - UserID::Gender::Age::Occupation::Zip-code  
    Movies.dat - Format - MovieID::Title::Genres  

Analysis Tasks to be performed:    

• Import the three datasets  

• Create a new dataset [Master_Data] with the following columns MovieID Title UserID Age Gender Occupation Rating.  

• Explore the datasets using visual representations (graphs or tables), also include your comments on the following:  

     1.User Age Distribution  
     2.User rating of the movie “Toy Story”  
     3.Top 25 movies by viewership rating  
     4.Find the ratings for all the movies reviewed by for a particular user of user id = 2696  

• Feature Engineering: Use column genres:  

    1.	Find out all the unique genres (Hint: split the data in column genre making a list and then process the data to find out only the unique categories of genres)  
    2.	Create a separate column for each genre category with a one-hot encoding ( 1 and 0) whether or not the movie belongs to that genre.   
    3.	Determine the features affecting the ratings of any particular movie.  

• Develop an appropriate model to predict the movie ratings.  
