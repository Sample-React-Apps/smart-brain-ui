## Face Recognition App

### Steps-
* Create the Navigation component.
* Create the Logo component and give styling using tachyeons.
* Add Tilt Logo using [React.js - Tilt.js](https://www.npmjs.com/package/react-tilt).
* Add Logo css to add styling.
* Create ImageLinkForm component.
* Add ImageLinkForm css for styling and add honey-comb css patttern from [css3 patterns](https://leaverou.github.io/css3patterns/#honeycomb).
* Create Rank component.
* Add particles to the backgroud of App using [Particle.js](https://vincentgarreau.com/particles.js/) & [React particles library](https://www.npmjs.com/package/react-particles-js).
* Create the state in App.js for input.
* Create FaceRecognition component and display image using API from [clarifi.com](https://docs.clarifai.com/api-guide/predict/images).

* Add FaceDisplayBox by first calculating face corrdinates and set the box data as the App state and pass box data to FaceRecognition component and add div to draw boundary box + add css for the boundary box.
* Add SignIn form from tachyons in Card and then use route as a state property to switch signIn and Home Page.
* Similarly add register component and add logic to switch between different routes.

* Convert SignIn component to smart component and add its state to store email & password.
* Add submit signin method to handle click of submit.

* Convert Register component to smart component and add its state to store user data.
* Add submit register method to handle click of submit.

## Backend [Node]
* Create a node project with npm init -y.
* Install express npm install express.
* Install nodemon as dev dependency npm install nodemon --save-dev.
* Install body-parser npm install body-parser.
* Add signin & register endpoint.
* Install cors package to avoid cross origin access problem.
* Add cros to app middleware.
* Install knex,pg to connect to the database.
* Replace all the local array operations with database queries.

https://d1qsx5nyffkra9.cloudfront.net/sites/default/files/article-image/eminence-organics-acne-face-mapping.jpg

## Database [PostgreSQL]
* brew update
* brew doctor
* brew install postgresql
* brew services start postgresql
* brew services stop postgresql
* createdb test / dropdb test
* psql test (to go into database)
* create table users(name text,age smallint,birthday date)
* \d to show the tables
* \q to exit to terminal
* create database, create tables.




This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

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

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify

### Changes for github deployment
"homepage": "https://anshulsaxena-93.github.io/facerecognitionbrain"
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
"start": "react-scripts start"