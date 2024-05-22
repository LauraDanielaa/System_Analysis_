## Documentation and analysis of the workshop_3

For this workshop_3 we want to create a movie recommendation site, so that a user enters certain characteristics that he/she would like to see in a movie and the system shows him/her the movies with those characteristics. For this, we took the information of the movies from a popular website called IMDb where there is different information about movies and opinions, however, to avoid spending money on a webAPI to recommend the movies to watch we used a method called web scrapping, which allows to obtain information using HTML from a website, and put this information in a DataFrame to facilitate the data processing.
In this case, we used the request package to get the HTML code from the IMDb site, the beautiful soup package to do web scraping, and pandas to have a dataframe to handle the data.

In the IMDb Upcoming Relases link there are upcoming movies with some related data like genre or star actors. So, using html tags, information was taken and stored in python variables.


## Analysis of the expert system

From the dataframe with the movie data, a decision tree can be made using the movie information. For this, it begins by asking the user the genre of the movie they would like to see, the options focusing on Action, Adventure, Animation, Biography, Comedy, Drama, History, Sci-Fi, Thriller. From this, you are asked about the year of the movie you want to see, of which you can choose between the years 2023 and 2024. Finally, to make better filtering, you are asked if you want there to be a specific actor. , which has to mark between yes or no and after the data is filtered all the movies with these characteristics. To achieve this, conditionals were used and filters were applied in Pandas dataframe.

The sensitivity of the movie recommendation system lies in the precision of the data extracted from the IMDb website, which guarantees accurate recommendations; updating data, which maintains the relevance of suggestions; the diversity of recommendations, which offers a wide selection of movies; and user interaction, which must be intuitive and satisfactory. These elements are crucial to providing an optimal user experience and ensuring that the system is effective and reliable in its recommendations.
