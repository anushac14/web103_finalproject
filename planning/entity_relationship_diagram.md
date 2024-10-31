# Entity Relationship Diagram

Reference the Creating an Entity Relationship Diagram final project guide in the course portal for more information about how to complete this deliverable.

## Create the List of Tables

[👉🏾👉🏾👉🏾 List each table in your diagram]

### User

| Column Name  | Type         | Description                  |
|--------------|--------------|------------------------------|
| user_id      | integer      | Primary key                  |
| username     | varchar(50)  | Username of the user         |
| email        | varchar(100) | User's email address         |
| created_at   | timestamp    | Account creation timestamp   |
| role         | varchar(10)  | User's role (admin, user)    |

### Playlist

| Column Name      | Type         | Description                         |
|------------------|--------------|-------------------------------------|
| playlist_id      | integer      | Primary key                         |
| name             | varchar(100) | Name of the playlist                |
| created_at       | timestamp    | Playlist creation timestamp         |
| created_by       | integer      | Foreign key referencing user_id     |

### Song

| Column Name   | Type         | Description                        |
|---------------|--------------|------------------------------------|
| song_id       | integer      | Primary key                        |
| title         | varchar(100) | Title of the song                  |
| artist        | varchar(100) | Name of the artist                 |
| genre         | varchar(50)  | Genre of the song                  |
| created_at    | timestamp    | Song record creation timestamp     |

### Collaborative Playlist (Join Table)

| Column Name   | Type    | Description                             |
|---------------|---------|-----------------------------------------|
| collab_id     | integer | Primary key                             |
| user_id       | integer | Foreign key referencing user_id         |
| playlist_id   | integer | Foreign key referencing playlist_id     |

### Song Playlist (Join Table)

| Column Name       | Type    | Description                             |
|-------------------|---------|-----------------------------------------|
| song_playlist_id  | integer | Primary key                             |
| song_id           | integer | Foreign key referencing song_id         |
| playlist_id       | integer | Foreign key referencing playlist_id     |

### Rating

| Column Name  | Type    | Description                             |
|--------------|---------|-----------------------------------------|
| rating_id    | integer | Primary key                             |
| user_id      | integer | Foreign key referencing user_id         |
| song_id      | integer | Foreign key referencing song_id         |
| playlist_id  | integer | Foreign key referencing playlist_id     |
| rating       | integer | Rating given by the user (e.g., 1-5)    |
| comments     | text    | User's comments on the song or playlist |


## Add the Entity Relationship Diagram

[👉🏾👉🏾👉🏾 Include an image or images of the diagram below. You may also wish to use the following markdown syntax to outline each table, as per your preference.]

![Entity Relationship Diagram](https://i.imgur.com/PbowmHg.png)
