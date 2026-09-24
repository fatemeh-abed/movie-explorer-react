# 🍿 Movie Explorer

A React movie application built as a hands-on project to practice **React Hooks, component design, composition, reusability, and working with a real-world API**.

The project was originally built as **usePopcorn** and is based on the idea of learning and applying React Hooks through a practical movie-search application.

## ✨ Features

* 🔎 Search for movies using the **OMDb API**
* 🎬 View detailed information about a selected movie
* ⭐ Rate movies using a custom star-rating component
* ❤️ Add rated movies to a personal watched/favorite list
* 📊 View statistics about the movies in the list
* 🗑️ Remove movies from the list
* ⌨️ Use the **Escape** key to close the movie details and go back
* 🚫 Prevent rating the same movie more than once
* 💾 Persist the movie list using **Local Storage**
* 🎨 Responsive and reusable component-based UI

## 🧠 What I Practiced

This project was mainly focused on understanding how to think about and structure React applications rather than simply building a movie search interface.

### React Hooks

The project uses several React Hooks to manage state, side effects, keyboard events, and reusable logic.

Some of the custom hooks include:

* `useMovies` — handles movie searching and API requests
* `useLocalStorageState` — synchronizes state with Local Storage
* `useKey` — handles keyboard events such as pressing Escape

It also uses built-in hooks such as:

* `useState`
* `useEffect`
* `useRef`

### Component Design

Practiced breaking a UI into smaller components based on their responsibilities.

For example:

* Movie search
* Movie list
* Movie item
* Movie details
* Star rating
* Watched movie list
* Watched movie statistics

This helped me understand **when a component should be split and how components should communicate with each other.**

### Composition

The project uses **component composition** to create flexible and reusable components instead of putting all the logic into a single large component.

### Reusability

Reusable components and custom hooks were created to avoid duplicating logic and to make the application easier to maintain.

### Building Layouts

Practiced building the application's layout from smaller UI components and organizing the relationship between:

* Navigation
* Search
* Movie results
* Movie details
* Watched list
* Statistics

## 🛠️ Tech Stack

* React
* JavaScript (ES6+)
* Create React App
* React Hooks
* Custom Hooks
* OMDb API
* Local Storage
* CSS
* HTML

## 🔄 How It Works

### 1. Search for a movie

The user enters a movie title in the search box. The application sends a request to the **OMDb API** and displays the search results.

### 2. Select a movie

Clicking on a movie opens its detailed information, including information such as:

* Title
* Poster
* Release year
* Runtime
* Genre
* IMDb rating
* Plot
* Actors
* Director

### 3. Rate the movie

The user can give the movie a personal rating using the star-rating component.

After submitting the rating, the movie is added to the watched list.

### 4. Watched list

The watched list keeps track of movies that have been rated.

The application also calculates statistics such as:

* Number of movies
* Average IMDb rating
* Average personal rating
* Average runtime

### 5. Local Storage

The watched movies are stored in **Local Storage**, so the list remains available after refreshing the page.

### 6. Keyboard interaction

Pressing the **Escape** key closes the selected movie and returns to the movie list.


## 🎯 Main Learning Goals

The main goal of this project was to move beyond simply writing React components and learn how to **design a React application**.

Through this project, I practiced:

* Thinking about component responsibilities
* Deciding when to split components
* Component composition
* Building reusable components
* Creating reusable custom hooks
* Managing state with React Hooks
* Handling side effects
* Working with APIs
* Persisting data with Local Storage
* Handling keyboard events
* Building a complete application layout
* Organizing application logic



## 🌐 Live Demo

https://fatemeh-abed.github.io/movie-explorer-react/



### Built with React ⚛️ and a lot of ☕
