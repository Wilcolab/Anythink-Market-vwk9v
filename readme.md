# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Install the latest version of docker and verify if its running by running the following:

> docker -v and docker-compose -v.

2. Go to the project root directory in order to load Anythink backend and frontend and run:

> docker-compose up

3. If the setup works correctly visit the following link [Ping](http://localhost:3000/api/ping) it should return the following message:

    {
        "msg":"Pong! Seems like Everythink is working, great job!"
    }

4. Check if the backend is connected to the frontend by Creating a new user using the [Register](http://localhost:3000/api/ping) endpoint.


Now you can run your project.

