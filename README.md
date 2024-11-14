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
 ✅ ### Login Feature (User Story 0):
 - User Feature: Users can log in to their own personal accounts


https://github.com/user-attachments/assets/8814854c-11b2-4457-b02e-27a07fa0e513


### Playlist Management (User Story 1): 
- User Feature: Users can create, edit, and delete playlists to manage their favorite songs.
- Technical Feature: Implement POST/GET requests for playlist creation, PATCH for editing playlists, and DELETE requests for playlist removal.
[gif goes here]
 ✅ ### Personalized Recommendations (User Story 2): 
- User Feature: Recommendations are generated based on the user's past listening habits and preferences.
- Technical Feature: Implement a recommendation algorithm that analyzes user data (listening history or selected genres) and returns recommendations via GET requests.
https://imgur.com/a/5whXQ3v
### Collaborative Playlists (User Story 3): 
- User Feature: Friends can collaborate on playlists, allowing multiple users to contribute songs.
- Technical Feature: Implement a many-to-many database relationship with a join table to link users to collaborative playlists. Use POST requests to add collaborators and DELETE to remove them.
[gif goes here]
### Concert Alerts (User Story 4): 
- User Feature: Notifications for upcoming concerts based on user preferences and favorite artists.
- Technical Feature: Set up a GET request to fetch concert data using an external API and match it with the user’s favorite artists, sending notifications.
[gif goes here]
### Music Filtering System (User Story 5): 
- User Feature: Users can filter recommendations by genre, mood, or activity.
- Technical Feature: Implement GET requests with query parameters that filter the music database by genre, mood, or activity.
[gif goes here]
### Cross-Device Syncing (User Story 6): 
- User Feature: Playlists sync across all devices for a seamless music experience.
- Technical Feature: Store playlists in a persistent database with a GET request to retrieve playlists based on the logged-in user’s data across devices. Implement session management with tokens.
[gif goes here]
### Social Sharing (User Story 7): 
- User Feature: Users can share playlists directly to social media platforms.
- Technical Feature: Implement a POST request that generates a shareable link and integrates with APIs from social media platforms (e.g., Facebook, Twitter) to share the link.
[gif goes here]
### Rating and Feedback System (User Story 8): 
- User Feature: Users can rate songs and provide feedback to improve the algorithm for future recommendations.
- Technical Feature: Implement POST requests to record user ratings and feedback, store them in the database, and refine the recommendation algorithm to adjust based on ratings.
[gif goes here]
### Listening History (User Story 9): 
- User Feature: Users can view their listening history to revisit favorite songs.
- Technical Feature: Implement a GET request that retrieves the user’s past listening data from the database, displaying it in their profile.
[gif goes here]
### Trending Playlists Section (User Story 10): 
- User Feature: A section where users can explore popular and trending playlists created by the community.
- Technical Feature: Implement a GET request to retrieve and display the most popular playlists from the database, based on metrics like number of listens, shares, or likes.
[gif goes here]


### [ADDITIONAL FEATURES GO HERE - ADD ALL FEATURES HERE IN THE FORMAT ABOVE; you will check these off and add gifs as you complete them]
Strech: Connect OpenAI API's to let users generate their own music or event/concert alert features.

## Installation Instructions

[instructions go here]
