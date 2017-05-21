# Google Assistant Node Boilerplate (Unofficial)

Boilerplate for building Google Assistant applications with NodeJS

## Install

After cloning the repository, run

`yarn install` or `npm install`

## API.AI

TODO: Fill this part in

## Building for production

`yarn run build` or `npm run build`, the build files will be in the `dist` directory

## Running a local server

`yarn run functions:start` then

`yarn run functions:deploy` then

`yarn run ngrok -- $PORT` (Where $PORT is replaced with the port from the output of the previous commands)

## Viewing logs from the local server

`yarn run logs:read`

`yarn run logs:clear`

## Useful commands

`yarn run flow` for static type checking with `flow`

`yarn run test` for testing with `jest`

`yarn run lint` for linting with `eslint`

`yarn run prettier` for code formatting `prettier`

TODO: Add images throughout to help explain the setup
