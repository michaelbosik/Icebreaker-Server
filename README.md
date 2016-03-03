# Server portion of the Icebreaker Project

This repo is for the Server of the Icebreaker Project. For more information on the Project see [Icebreaker-App](https://github.com/Icebreaker-Project/Icebreaker-App).

This server is to be written in Python on MongoDB(needs review) and Nginx.

As for hosting... most likely Amazon AWS free or Heroku.

## Server outline
- When user creates new room it adds a table to the database.
- When a person joins the room it adds their information to the table as a new user
- The server coordinates the games but the games themselves are run in the app.
