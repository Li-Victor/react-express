# react-express

A simple express and react boilderplate. It uses create-react-app and can run create-react-app scripts from the root directory (Do not have to change directories to change React code). React code is located inside the views folder.

## Installation
First [**yarn**](https://yarnpkg.com/en/) must be installed globally. </br>
Then run the command in the terminal `yarn setup`. </br>
Next run `yarn build` and then `yarn start`.

## Available Scripts
**`yarn start`**

Runs just express application. Open [**http://localhost:3000**](http://localhost:3000) to view it in the browser. </br>
Important to run `yarn build` before running this script.

**`yarn build`**

Builds and bundles the create-react-app to craete a build folder in the views folder. </br>
Run this script before you use `yarn start`.

**`yarn setup`**

Installs all the necessary dependencies. 

**`yarn react-dev`**

Runs create-react-app in development mode. Open [**http://localhost:3000**](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.

**`yarn react-text`**
Launches create-react-app test runner in the interactive watch mode.

All other information about create-react-app can be found in https://github.com/facebookincubator/create-react-app/.

Example of this project setup:
* [**React password**](https://github.com/Li-Victor/react-password) inspired by blog post https://daveceddia.com/create-react-app-express-production/
* [**Voting app**](https://github.com/Li-Victor/lets-vote)
