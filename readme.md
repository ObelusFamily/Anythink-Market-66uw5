# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker and run the commands in the terminal.
2. Once installed you can verify docker is ready by running docker -v and docker-compose -v.
3. Then run docker-compose up from the project root directory to load Anything's backend and frontend. 
4. You can now test this to http://localhost:3000/api/ping.
