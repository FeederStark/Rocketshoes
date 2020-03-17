This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Starting app

First, you will need to clone/download this repository and run `yarn install`.
Then, you must run `npx json-server db.json --port 3333`. The api will be running on `http://localhost:3333`.
After running your api on port 3333 you run `yarn start`.

## Functionalities

This is a simple one-page-application choose and buy shoes from a catalog.
First, the application will fetch all the data from the api and show them in a grid, and you can either keep adding new shoes or go straight to your cart.
This is a really simple application just to show the use of redux/redux-saga.

## Tools used

This is a list of the tools used to make this application.

- styled-components. This is used to style most of the application components.
- axios. We use axios to make the api calls.
- redux and react-redux. To use a global store and make the flux of data flow better.
- redux-saga. To make asynchronous calls.
- eslint. Eslint is used to make the code have a solid pattern.
- editorconfig. Editorconfig also helps with having a solid pattern between the devs.
- react-toastify. This is used to prompt successfull/error messages to the user.
- reactotron. To help debug the application.
- immer. To minimize some of the redux code.
- json-server. To create a small api to work with.
