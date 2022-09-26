# React Node.js Project Template

A custom made boilerplate code for a React/Node.js project. 

The Node.js server is in the `server` directory, and the React app is in the `client` directory and is based on `npx create-react-app`. 

The general file structure and notable changes are listed below

- `react-node-template`: project home directory
 - `client`: directory containing React app
   - `public`: directory containing public/static assets
     - `index.html`: file containing stylesheet references for google icons and font
   - `src`: directory containing code for React components
     - `components`: directory containing code for a sample component
     - `scripts`: directory containing a utils file
     - `styles`: directory containing stylesheets for components and general mixins
       - `mixins`: directory containing a mixins file
         - `mixins.scss`: file containing scss functions and default styling for the app
       - `comp-sample.scss`: file containing scss for the sample component
       - `main.scss`: file containing global style and calls default functions from mixins.scss
     - `App.js`: file containing the main component of the React app
     - `SetupProxy.js`: file defining a local proxy to the Node.js server.
 - `server`: directory containing the Node.js server
   - `index.js`: file that defines the server and the api routes
     - `scripts`: directory containing a utils file
 - `.env.example`: example of .env
 - `.gitignore`: ignores .env and node_modules directory
 - `README.md`: project description
 - `package.lock.json`: created by package.json
 - `package.json`: contains project info, packages, dependencies, and scripts
  
## Available Scripts

All scripts below are run from the project directory.

### Run the Node.js server

`npm start`

This will start the Node.js server on port 8888.

### Run the React client app

`cd client`

`npm start`

This will start the React client app on port 3000.

## IMPORTANT NOTES

The content above is a readme for the React Node.js Project Template and should be removed when creating a new project.
The content below is a basic template for the readme created for a new project. Please make any necessary changes to the template below that are reflected in the project, such as:
- changing scripts
- changing ports
- changing environment vars
- changing hosting services
- changing deployment process

# New Project Title

New project description text
  
## Deployed Application

This application is deployed and hosted on host (change text of 'host' to Heroku/Github Pages/other hosting service) and can be viewed 
here (attach a link to 'here').

## Available Scripts

All scripts below are run from the project directory.

### Run the Node.js server

`npm start`

This will start the Node.js server on port 8888.

### Run the React client app

`cd client`

`npm start`

This will start the React client app on port 3000.

## Deploying The Project

The deployed project is based on the `main` branch, and a new deployment occurs when updates are pushed onto the `main` branch.
