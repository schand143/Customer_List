This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# Step 2 — Creating a JSON Server

In this step, you’ll create a mock server that your React application can quickly connect with, as well as use its resources. It is important to note that this back-end service is not suitable for an application in production. You can use Nest.js, Express, or any other back-end technology to build a RESTful API in production. json-server is a useful tool whenever you need to create a prototype and mock a back-end server.

You can use either npm or yarn to install json-server on your machine. This will make it available from any directory of your project whenever you might need to make use of it. Open a new terminal window and run this command to install json-server while you are still within the project directory:

### yarn global add json-server

Next, you will create a JSON file that will contain the data that will be exposed by the REST API. For the objects specified in this file (which you’ll create), a CRUD endpoint will be generated automatically. To begin, create a new folder named server and then move into it:

mkdir server

cd server

## Now, use nano to create and open a new file named db.json:

nano db.json

The JSON structure consists of a customer object, which has two datasets assigned. Each customer consists of seven properties: id, description, first_name, last_name, email, phone, and address.

Save and exit the file.

By default, the json-server runs on port 3000—this is the same port on which your React application runs. To avoid conflict, you can change the default port for the json-server. To do that, move to the root directory of the application:

cd ~/typescript-react-app

Open the application with your preferred text editor and create a new file named json-server.json:

nano json-server.json

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
