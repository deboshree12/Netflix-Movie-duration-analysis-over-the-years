# Overview 
The aim of this project is to analyze a dataset of movies on Netflix and investigate how movie lengths and genres have changed over time. The report uses Python programming language and various libraries such as pandas and matplotlib to perform data analysis and visualization.

## Libraries Used
- ```pandas```
- ```matplotlib.pyplot```

## Datasets Used
Netflix movie data (CSV file)

## Methods

The analysis involved several steps:

- Creating a list of years (from 2011 to 2020) and a list of movie durations (how long each movie is, in minutes), and combining these lists into a dictionary.
- Converting the dictionary into a pandas DataFrame using the pandas library, and printing the DataFrame to the screen.
- Reading in the Netflix movie data CSV file using the pandas library, and printing the first five rows of the DataFrame to the screen.
- Subsetting the DataFrame to only include rows where the "type" column is equal to "Movie" and selecting only the columns of interest (like the title of the movie, what country it's from, what genre it is, and how long it is) to create a new DataFrame, and printing this DataFrame to the screen.
- Creating a scatter plot of movie duration versus release year for the movies in the new DataFrame using the matplotlib library, and showing the plot on the screen.
- Filtering for movies with a duration shorter than 60 minutes and printing the first 20 rows of this subset to the screen.
- Iterating over the rows of the DataFrame, appending a color to a list based on the genre of the movie.
- Creating another scatter plot of movie duration versus release year, coloring the points based on their genre, and showing the plot on the screen.

## Results

The analysis produced several key findings:

1. The years and durations of movies on Netflix were summarized in a table, showing that the average length of movies has decreased slightly over time.
<img width="453" alt="Screenshot 2023-03-23 at 2 52 54 PM" src="https://user-images.githubusercontent.com/49270107/227343037-f65490c5-909c-4b4b-9822-07dd829e1357.png">

2. A scatter plot of movie durations versus release years was created, which showed a slightly downward trend in movie length over time.
<img width="803" alt="Screenshot 2023-03-23 at 2 53 14 PM" src="https://user-images.githubusercontent.com/49270107/227343115-73d10dda-ab7a-4474-8856-a0116f6ebef6.png">

3. A new table of movie titles, genres, countries, release years, and durations was printed to the screen, showing that most of the movies on Netflix are from the United States and that the most common genres are drama, comedy, and documentary.

4. A scatter plot of movie durations versus release years was created again, this time with different colors for different genres. The plot showed that documentaries tend to be longer than other genres and that the duration of comedy movies has decreased over time.
<img width="803" alt="Screenshot 2023-03-23 at 2 53 33 PM" src="https://user-images.githubusercontent.com/49270107/227343211-b0f55896-a8ab-4471-af1e-0b273339915a.png">

5. A subset of the DataFrame that includes only movies with a duration shorter than 60 minutes was created, and the first 20 movies in this subset were printed to the screen. The results showed that most of the short movies on Netflix are documentaries and stand-up comedies.

## Conclusion

In conclusion, this analysis showed that the length of movies on Netflix has decreased slightly over time, and that the most common genres on Netflix are drama, comedy, and documentary. The analysis also revealed that documentaries tend to be longer than other genres, and that the duration of comedy movies has decreased over time. The findings suggest that the movie industry is changing, and that shorter movies are becoming more popular. However, further research is needed to determine whether or not this trend will continue in the future.


