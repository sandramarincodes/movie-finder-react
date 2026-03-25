# 🎬 Movie Finder

A React app that helps users discover movies with a smart search experience powered by TMDB and Appwrite.

## 🌐 Live Demo

👉 [sandramarincodes.github.io/movie-finder-react](https://sandramarincodes.github.io/movie-finder-react/)

## 📝 About the Project

Movie Finder is a frontend project built with React that consumes the TMDB API to search and display movies. It uses Appwrite as a Backend-as-a-Service to persist search analytics — tracking which terms users search most and avoiding duplicates — while keeping React focused on UI and state.

## ✨ Features

- Search movies in real time using the TMDB API
- Debounced search to optimize API calls and improve performance
- Search analytics stored in Appwrite (trending terms, no duplicates)
- Clean and responsive UI

## 🛠️ Tech Stack

- **React** — UI and state management
- **Vite** — build tool
- **TMDB API** — movie data
- **Appwrite** — Backend-as-a-Service for search analytics
- **CSS** — custom styling

## 🚀 Getting Started

### Prerequisites

- Node.js
- npm
- A [TMDB API key](https://www.themoviedb.org/)
- An [Appwrite](https://appwrite.io/) project set up

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/sandramarincodes/movie-finder-react.git
   cd movie-finder-react
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add the necessary keys for TMDB and Appwrite

4. Start the development server

   ```bash
   npm run dev
   ```

## Contact

[sandramarincodes](https://github.com/sandramarincodes)
