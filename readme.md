# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Step1: Install Docker and the latest update for WSL 2 kernel.
Step2: Go to the root directory and use "docker-compose up" command to deploy the frontend andbackend locally.
Step3: Go to http://localhost:3000/api/ping to check backend.
Step4: Go to http://localhost:3001/register to check frontend.
Step5: Register to make sure if the frontend and backend are connected.
