# Bill Manager - React.js, Redux, Chart.js


- - -



- - -
## Problem Statement:

Adithya owns a car wash business and needs help to manage various bills from his vendors.
Build an application to help Adithya manage his monthly bills.


## The app uses following libraries/packages for development, build and deployment:

- **[React.js](https://reactjs.org/)** - An open-source JavaScript library for building user interfaces & single-page or mobile applications.
- **[Redux.js](https://redux.js.org/)** - A Predictable State Container for JS Apps
- **[Redux-Saga](https://redux-saga.js.org/)** - A Redux Middleware library to handle Asynchronous Actions such as fetching data more easily & effciently
- **[React-Router](https://www.npmjs.com/package/react-router)** - A package that provides the core routing functionality for React Router
- **[Chart.js](https://www.chartjs.org/)** - an open-source JavaScript library to draw different types of charts by using the HTML5 canvas element
- **LocalStorage** - Not a library but a feature that this app uses local storage to store data(temporary storage) and to maintain the new bill id
- **[Docker](https://www.docker.com/)** - to package and run the app in a loosely isolated environment called a container
- **[Vercel (formerly ZEIT)](https://vercel.com/)** - for Instant static deploys
- **[TypeScript](https://github.com/Microsoft/TypeScript)** - a superset of JavaScript programming language that compiles to clean JavaScript output.





## Screens:

1. **Overview Page** - Shows monthly bills in a graph

![Overview](overview-graph.PNG)



2. **Create/Edit Bill Screen** - Create or edit bills on this screen using a simple form

![Create/Edit Bill](create-new-bill-form.PNG)




3. **List all Bills Screen** - Create or edit bills on this screen using a simple form

![List all Bills Screen](all-bills-list.PNG)





Here's a screenshot to show how local storage will look like:


![localstorage](local-storage-data.PNG)





This project is bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:


### `npm install`

Installs the important libraries to build and run the app.<br />

In case of any issue while building the app, delete the `node_modules` folder in the root directory and run this command again.


### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.




