# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the github repository
2. Install docker (You can if it is properly installed by running the command <code>docker -v</code> and <code>docker-compose -v</code>)
3. Go to project root 
4. Run the command <code>docker-compose up</code>

After that check docker is working correctly

If Docker is working correctly, the backend should be running and able to connect to your local database.
Test this by pointing your browser to http://localhost:3000/api/ping

Then check front end is working properly
If it is working properly then you can go to http://localhost:3001/register and create an account

