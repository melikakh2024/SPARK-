
**PySpark Movie Ratings Analysis**

This project demonstrates ETL and analytics using PySpark on a movie rating dataset. It covers data loading, transformation, aggregation, and visualization with word clouds.  

**📂 Project Overview**
Loads multiple CSV files (movies.csv, ratings.csv, links.csv, tags.csv) containing information about movies, users, ratings, and tags.  

Joins datasets to create a clean, unified dataset with columns such as:  

movieId, title, genres, userId, rating, tags, review_timestamp, imdbId, tmdbId  
Performs aggregations to calculate average, max, min ratings, and review counts per movie.  
Generates IMDb links for each movie.  
Creates word clouds for movies and genres to visualize popularity.  
**⚙️ Key Features**  
ETL with PySpark: Efficient handling of large CSV files and joining multiple datasets.  
**Aggregated metrics:**  
Average Rating  
Maximum Rating  
Minimum Rating  
Number of Reviews per movie  
**WordCloud Visualizations:**  
Most frequently reviewed movies  
Most common genres  
Data Ready for Analysis: Final dataset and views are prepared for BI tools or further analytics.  
**🗂 Input Data**  
CSV files located in: ./data/rating/  
movies.csv  
ratings.csv   
links.csv   
tags.csv  
Each file contains essential information to build a comprehensive movie rating dataset.  
**🏁 Output**  
Final DataFrame / Table with aggregated movie ratings and IMDb links.  
WordCloud visualizations for movies and genres showing frequency and popularity trends.  
Spark SQL view movie_view to query aggregated metrics.  
**⚡ Prerequisites**  
PySpark  
Python libraries: pandas, matplotlib, wordcloud  
Jupyter Notebook or any Python environment supporting PySpark  
**📌 How to Run**  
Place CSV files in the ./data/rating/ folder.  
Start a PySpark session.  
Run the ETL and aggregation scripts to prepare the dataset.  
Generate word clouds for movies and genres.  
