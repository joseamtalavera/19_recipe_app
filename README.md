# Recipe App

This project is a Recipe App bootstrapped with [Create React App](https://github.com/facebook/create-react-app). The app lists a variety of recipes, allowing users to select their favorite ones.

## Redux Toolkit

The state management of this application is handled using Redux Toolkit (RTK), a package that simplifies the process of setting up and using Redux in a React application. It includes several functions that implement best practices, prevent common mistakes, and make it easier to write Redux code.

Key features of Redux Toolkit used in this application include:

- **createSlice()**: This function helps to simplify Redux reducer logic and actions. It takes a configuration object as a parameter, which includes properties like `name`, `initialState`, and `reducers`.

- **configureStore()**: This function simplifies the store setup process. It wraps around the Redux core `createStore()` function and the `combineReducers()` function, handling most of the store setup automatically.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`
