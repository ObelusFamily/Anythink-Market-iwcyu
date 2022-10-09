# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

### Steps:
    -   Run *docker-compose* up in your terminal to load Anythink's backend and frontend.
    -   Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
    -   Test if it works pointing your browser to https://obelusfamily-anythink-market-iwcyu-7qg4r6rgpg2xj9r-3000.githubpreview.dev/api/ping
    -   The backend should be up and running.