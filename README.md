## Summary

- This was a project that needed to complete for CMPUT 291 (Introdcution to File and Database Management)
- This project was to build an CLI for admins to manage the movies, movies rating and movies principals in the database. The admins can perform following the action:
  - Add a new cast / crew member
    - Associate this cast / crew member to a movie in the database
  - Add a new movie:
    - Associate cast / crew members to this movie, or add new cast / crew members on the fly
  - Search for movies and cast / crew members based on given critera and filters
- This project was written purely in python and all data was stored in MongoDB.
- This project also aimed to build query with fast access in MongoDB by building indices since it's a requirement of this project where query time must not reach a specific thersold. 