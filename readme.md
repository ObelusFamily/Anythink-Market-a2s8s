# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Requirements

- Docker "https://docs.docker.com/get-docker/"
- git 

### Steps 

- Clone or download the repo
- Get into the repo and run `docker-compose up` or `docker-compose up -d` for detachable mode
- Check the ping site running locally -- http://localhost:3000/api/ping
- Register a new user on http://localhost:3001/register  when its available
- Done. You have your local testing environemnt ready