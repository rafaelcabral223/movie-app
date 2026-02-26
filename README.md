# Movie App

![](https://github.com/user-attachments/assets/86a38ab3-31f3-4c56-9804-0fa81e6a3e40)

| :placard:  |                                       |
| --------------------- | ------------------------------------- |
| :sparkles: Name       | **Movie App**                         |
| :label: Technologies  | html, css, javascript, TMDB API       |
| :rocket: URL          | https://moviesapplicationtmdb.netlify.app/                         |

## About

This project is a web application that displays popular movies and lets users search for specific titles using The Movie Database (TMDB) API. The interface shows movie cards with poster, rating, and overview.

## Features

- Initial list with popular movies
- Search movies by title
- Average rating displayed with color-based classification
- Overview appears when hovering over a movie card
- Back button to return to the initial movie list

## How It Works

1. When the page loads, the app requests popular movies from the API.
2. Results are rendered as cards with poster image, title, and rating.
3. When a search is submitted, the app queries the API using the typed term.
4. The rating color is assigned automatically:
	- **Green** for high ratings
	- **Orange** for medium ratings
	- **Red** for low ratings