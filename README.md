# Analysis-of-RSVP-Productions-Movies-Using-MySQL

## **Introduction**

The IMDB database is one of the most comprehensive and well-known movie databases, providing detailed information about films, their ratings, cast, crew, and much more. This project involves creating a smaller version of the IMDB database. By analyzing the database, users can gain insights into movie trends, director collaborations, and rating distributions.

## **Problem Statement**

The goal is to design and populate a lightweight version of the IMDB database to enable analysis of movie, genre, director, role, and ratings data. This database is intended for SQL assignments or projects requiring relational database design and complex queries.

## **Objective**

The aim is to create a simplified version of the IMDB database using MySQL. This includes:
1. Designing the database structure with appropriate tables and relationships.
2. Populating the database with sample data for meaningful analysis.
3. Enabling detailed queries to extract insights about movies, directors, genres, ratings, and more.

## **Data Sources**

The project involves creating the database and populating it with sample data for analysis:
1. **Movies Data**: Details such as title, year, country, and production company.
2. **Genres**: Categorization of movies by their genre(s).
3. **Directors and Roles**: Mapping of movies with directors and roles (actors, writers, etc.).
4. **Ratings**: Information about movie ratings, including average, median, and vote count.

## **Database Structure**

The database is structured into six key tables:

- **Movie**: Stores details about movies, such as title, year, and production.
- **Genre**: Represents the genre(s) for each movie.
- **Director Mapping**: Links movies with their directors.
- **Role Mapping**: Maps movies to individuals with roles (e.g., actors, writers).
- **Names**: Contains details about individuals, such as actors and directors.
- **Ratings**: Stores statistical data on movie ratings.

## **Queries and Key Metrics**

- **Top Movies by Rating**: Identify movies with the highest average ratings.
- **Highest Grossing Movies**: Analyze worldwide gross income for top-performing movies.
- **Yearly Trends**: Determine the most successful years in terms of movie releases.

### **Director and Actor Analysis**
- **Most Frequent Collaborations**: Analyze repeated collaborations between directors and actors.
- **Top Directors**: Identify directors with the highest-rated movies.

### **Genre Analysis**
- **Popular Genres**: List the most frequent genres in the dataset.
- **Genre Distribution**: Display the count of movies per genre.

### **Rating Insights**
- **Highest Rated Movies**: Identify movies with the best average and median ratings.
- **Vote Trends**: Analyze the distribution of votes for highly rated movies.

## **Key Insights**

### **Best-Performing Movies**
- **Movies with High Ratings**: Films like "Der müde Tod" have exceptional ratings and audience votes.
- **Most Popular Genres**: Genres such as Drama, Comedy, and Action are among the most represented.

### **Top Directors and Actors**
- **Directors**: Prominent directors with multiple top-rated movies include James Mangold.
- **Actors**: Key actors who consistently deliver high-rated performances include Vijay Sethupathi.

### **Genre Trends**
- Drama and Action are the most prevalent genres, often associated with high box office performance.

### **Ratings Breakdown**
- The database reveals that movies with multilingual support tend to attract a broader audience, impacting ratings positively.

## **Conclusion**

This project delivers a functional SQL database that captures the core elements of the IMDB system. By providing a structured and populated database, users can perform various analyses to derive insights into movies, directors, genres, and ratings. These scripts offer a robust starting point for SQL learners and analysts to explore relational database management and querying techniques.
