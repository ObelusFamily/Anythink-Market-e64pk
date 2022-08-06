# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Steps to install a fresh copy of this application:

1. `git clone` this repo
1. Install [Docker](https://docs.docker.com/get-docker/) if not already installed
1. Start the application using `docker-compose up`
1. Test backend - [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
1. Register a new user at frontend URL - [http://localhost:3001/register](http://localhost:3001/register)
