# Cinema Mon Amour

## Mobile Application for Movie Tracking

The Cinema Mon Amour mobile application was created during college as a project for the course **Mobile Application Programming**.

The application serves the purpose of keeping track of movies, allowing the user to monitor their favorite watched films.

The project was developed in Android Studio, and **Java** was chosen as the programming language. The application incorporates knowledge of using activities, adapters, fragments, listeners, model creation, and network usage.

[![My Skills](https://skills.thijs.gg/icons?i=androidstudio,java,sqlite)](https://skills.thijs.gg)

The chosen database is the local **Room** database, and for fetching movie data, **Retrofit** is used, which connects to the [TMDb API](https://www.themoviedb.org/documentation/api).

---

### In the application, you can:

- View a list of movies.
- Explore movie details (release date, IMDb rating, and description).
- Add movies to favorites and assign a personal rating to each movie.
- Browse through favorites, where all added movies are visible.
- Remove movies from favorites.

---

### Project Setup

To run the project, you need to create your own _api key_ on the official **TMDb API** website. Then, paste the obtained _api key_ into `cinemamonamour/fragments/Pop_Movies_Fragment.java`, inside:

```sh
public static final String API_KEY = "";
```
