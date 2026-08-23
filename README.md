# CineScope

CineScope is a beginner-friendly Movie Explorer web application created as the foundation project for the Fork 'nd Roll coding event.

The app uses local movie data, reusable React components, and simple CSS so students can understand the codebase quickly and extend it through Git and GitHub tasks.

## Features

- Responsive navigation bar
- Featured movie hero section
- Movie collection built with reusable cards
- Basic title search
- Movie details pages
- Local mock movie data
- Responsive layout for desktop, tablet, and mobile

## Tech Stack

- React.js
- Vite
- JavaScript
- HTML5
- CSS3
- React Router

## No Backend

Movie information is stored using **local mock data**.

---

## Installation

Install the project dependencies:

```bash
npm install
```

## Run the Project

Start the local development server:

```bash
npm run dev
```

Vite will print a local URL in the terminal. Open that URL in your browser.

## Project Structure

```text
cine-scope/
|-- public/
|   `-- posters/
|-- src/
|   |-- assets/
|   |-- components/
|   |   |-- Navbar.jsx
|   |   |-- MovieCard.jsx
|   |   |-- MovieGrid.jsx
|   |   `-- Footer.jsx
|   |-- data/
|   |   `-- movies.js
|   |-- pages/
|   |   |-- Home.jsx
|   |   `-- MovieDetails.jsx
|   |-- App.jsx
|   |-- main.jsx
|   `-- index.css
|-- package.json
|-- README.md
`-- .gitignore
```

## Main Components

`Navbar.jsx` contains the site navigation and a small search form.

`MovieCard.jsx` displays one movie with its poster, title, genre, year, rating, description, and details link.

`MovieGrid.jsx` receives a movie list and renders multiple `MovieCard` components.

`Home.jsx` shows the featured movie, search field, and movie collection.

`MovieDetails.jsx` reads the movie id from the URL and displays full information for that movie.

`movies.js` stores all local movie data separately from the UI.


# Fork ’nd Roll — Movie Explorer

Participants are expected to demonstrate proper use of:

* Repository forking
* Git cloning
* Branching
* Meaningful commits
* Pushing changes
* Pull Requests
* Repository organization
* GitHub workflow

---


# Existing Features

## 1. Navigation Bar

The application contains a responsive navigation bar with:

* CineScope logo/name
* Home
* Movies
* Search

---

## 2. Hero Section

The homepage contains a featured movie section with:

* Movie title
* Description
* Genre
* Rating
* View Details button

---

## 3. Movie Collection

Movies are displayed using reusable movie cards.

Each movie card contains:

* Movie poster
* Movie title
* Genre
* Release year
* Rating
* Description
* View Details button

The project should contain approximately **12–15 movies** in the local dataset.

---

## 4. Movie Details

Users can select a movie to view its details.

The details page contains:

* Movie poster
* Title
* Description
* Genre
* Release year
* Rating
* Duration
* Director
* Cast

---

## 5. Basic Search

The foundation project includes basic movie search functionality.

Users can search movies using their **title**.

---

## 6. Responsive Design

The application should work reasonably well on:

* Desktop
* Tablet
* Mobile

CSS media queries should be used to provide a responsive layout.

---

# Movie Data

Movie information should be stored locally.

Each movie should contain fields similar to:

```javascript
{
  id: 1,
  title: "Example Movie",
  genre: "Action",
  year: 2025,
  rating: 8.2,
  duration: "2h 10m",
  director: "Example Director",
  cast: ["Actor One", "Actor Two"],
  description: "Short movie description.",
  poster: "..."
}
```

The dataset should contain approximately **12–15 movies**.

---