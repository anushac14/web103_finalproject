# MelodyMix

CodePath WEB103 Final Project

Designed and developed by: Anusha Chinthamaduka, Vinh Le, Rajashekar V

🔗 Link to deployed app:

## About

### Description and Purpose

This application aims to enhance users' music experience by providing personalized playlist creation based on their unique tastes and preferences. By analyzing user input, it offers tailored music recommendations that encourage exploration of new artists and genres. Additionally, the platform fosters community engagement through collaborative playlists, allowing friends to curate shared musical journeys together.

### Inspiration

Inspired by the joy of discovering new music and sharing it with friends, this platform aims to create a dynamic space where users can explore diverse sounds and connect through shared playlists. The goal is to transform music discovery into a collaborative experience, fostering a sense of community among music lovers.

## Tech Stack

Frontend:
- React.js
- CSS Framework: TailwindCSS or Bootstrap
- Axios (or Fetch API): HTTP requests to the backend to perform CRUD operations (Create, Read, Update, Delete) on user data (like playlists, song preferences, etc.).
- React Context API (or Redux): For managing global state like user data, playlists, and shared preferences.

Backend:
- Node.js with Express.js
- Railway-PostgreSQL
- Deployment: Railway
  
## Features

### ✅ Playlist Management (User Story 1): 
- User Feature: Users can create, edit, and delete playlists to manage their favorite songs.
- Technical Feature: Implement POST/GET requests for playlist creation, PATCH for editing playlists, and DELETE requests for playlist removal.

https://github.com/user-attachments/assets/ec85f54c-1d0e-4001-ac68-65abad8a8893

###  ✅ Personalized Recommendations (User Story 2): 
- User Feature: Recommendations are generated based on the user's past listening habits and preferences.
- Technical Feature: Implement a recommendation algorithm that analyzes user data (listening history or selected genres) and returns recommendations via GET requests.
  
Link to demo: https://imgur.com/a/5whXQ3v

### ✅ Music Filtering System (User Story 3): 
- User Feature: Users can filter songs based on artist, genre, etc
- Technical Feature: Implement GET requests with query parameters that filter artist, genre, and more

https://github.com/user-attachments/assets/9503483e-3812-4c84-971a-ed1604c583b9


### [ADDITIONAL FEATURES GO HERE - ADD ALL FEATURES HERE IN THE FORMAT ABOVE; you will check these off and add gifs as you complete them]
Strech: Connect OpenAI API's to let users generate their own music or event/concert alert features.

## Installation Instructions

[instructions go here]
