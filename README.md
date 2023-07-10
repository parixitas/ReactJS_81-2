
# Harry Potter Character List

A JSON-based API for getting information on Harry Potter characters and spells.

Hosted at https://hp-api.onrender.com/
(Heroku free hosting tier support ended on November 28, 2022, as announced here)

## Prerequisites

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

### Install create-react-app
Install create-react-app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app

```bash
npm install -g create-react-app
```

## Cloning and Running the Application in local

Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```
In order to run the application Type the following command

```bash
npm start
```
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
The Application Runs on **localhost:3000**

## Application design

#### Components

1. **Header** Component : This Component Displays Search bar and Howard Student or Howard Staff Button. Search section is finding harry potter character.

2. **Cart** Component : This Component displays a list of Harry Potter Character List. This Component gets the data from a json file in ApiSlice folder

#### HTTP client

**axios** library is used to make HTTP Calls

#### URL

The application has just one url https://hp-api.onrender.com/ which ties to *Cart* Component

## Resources

**create-react-app** : The following link has all the commands that can be used with create-react-app
https://github.com/facebook/create-react-app

**ReactJS** : Refer to https://reactjs.org/ to understand the concepts of ReactJS

**Redux ToolKit** : Refer to https://redux-toolkit.js.org/ to understand the concepts of Redux Toolkit

