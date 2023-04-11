# Analyze-movies-data-from-IMDB

This project analyzes the IMDB movies dataset and provides insights on different aspects such as genres, ratings, awards, budget, and more. The project is written in Python and uses popular data analysis libraries such as Pandas and Matplotlib.

# Dataset
The IMDB movies dataset is available on Kaggle. It contains information on over 85,000 movies, including their titles, release dates, genres, ratings, budgets, and more.

# Functions
Here are the functions that are provided in this project:

group_movies_by_genre() - groups movies by genre

top_bottom_by_metascore(n, top=True) - returns the top/bottom n percentage movies according to metascore
top_bottom_by_imdb_rating(n, top=True) - returns the top/bottom n percentage movies according to IMDb user ratings
get_oscar_winners(year) - returns the list of movies that won an Oscar in a given year

get_budget_stats(n) - returns the n movies with highest/lowest budgets

get_movies_per_year() - returns the countries with the highest number of movie releases each year

analyze_rating_vs_awards() - analyzes the relationship between IMDb user rating and the number of awards received

get_akas(movie=None, region=None) - returns the alternate titles (AKAs) of a specified/all movies in specified/all regions

get_movies_by_year(year, before=False, after=False) - returns the movies released on, before, or after a given year

get_director_with_most_oscar_wins() - returns the director who has directed the most number of Oscar-winning movies

output_data(format="csv") - a wrapper function that returns the output in CSV or JSON format

(Optional) get_genre_stats() - returns statistics for each genre, such as average budget, most common director, and most common cast member (actor)

# Contact:

If you have any questions or feedback, please contact me at my email address: pbadave9@gmail.com
