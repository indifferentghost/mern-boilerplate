# Basic MERN Boilerplate

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Enviornment
Since this is a MERN boilerplate it does expect a mongoDB connection url. See `.env.example` in `/config`.
environments are split up -> the environment for dev is `.env.development` and prod is `.env.production`.
```.env
PORT=8000
MONGO_CONNECTION_STRING=
```
## Starting the app:
This boilerplate has a few scripts. It uses [`npm-run-all`](https://www.npmjs.com/package/npm-run-all) to run multiple scripts in parallel or sequence, check the `package.json` for more information.

| Command | Effect |
| :-- | --- |
| `dev:start` | Starts React and the node express server in development environment |
| `dev:server:start` | Starts the express server in development environment |
| `start` | Starts the server in production mode (This expects the React app to have been built) |
| `build` | Runs available tests before building the react application |
