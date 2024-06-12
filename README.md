# PUNITI_ECELL

1. Structures:
   - User: Represents a user with an ID, username, and a vector of genre preferences.
   - Movie: Represents a movie with an ID, title, genre, and release year.
   - UserRating: Represents a users rating for a movie, containing the user ID, movie ID, and rating.

2. Class MovieRecommendationSystem:
   - This class encapsulates the functionality of the movie recommendation system.
   - Private members:
     - users, movies, and userRatings: Vectors to store instances of User, Movie, and UserRating, respectively.
   - Public methods:
     - registerUser: Registers a new user with their ID, username, and genre preferences.
     - addMovie: Adds a new movie with its ID, title, genre, and release year.
     - rateMovie: Records a users rating for a movie.
     - recommendMovies: Recommends movies based on a given users profile. It checks for movies with matching genres to the users preferences and recommends movies that have been highly rated by other users.

3. main Function:
   - In the main function, an instance of MovieRecommendationSystem is created.
   - Users are registered with their IDs, usernames, and genre preferences.
   - Movies are added to the system with their IDs, titles, genres, and release years.
   - Movies are rated by the users.
   - Recommendations are generated for each user based on their preferences and ratings.
   - The recommended movies for each user are printed to the console.

4. Output:
   - The code outputs the recommended movies for the users "Puniti" and "Aastha" based on their preferences and ratings.

Overall, this code provides a basic implementation of a movie recommendation system where users can register, rate movies, and receive recommendations based on their preferences and the ratings of other users.
