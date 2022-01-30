# Welcome to the Anythink Market repo


## Prerequisites
1. Our backend server requires a live MongoDB server.
You can setup a local docker-based server by using the following command:
`sudo docker run --name my-mongo -p 27017:27017 -d mongo`

2. Place a .env file under `/backend` with your MongoDB endpoint for example:
`MONGODB_URI='mongodb://127.0.0.1/my_database'`

## Setup 

To install all dependencies use: `yarn install && yarn run setup`, it'll install both backend and frontend dependencies.

## Getting started
To start the app use: `yarn start`, it'll start both the backend and the frontend.
The webApp should be browsable at http://localhost:8000

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
