
🚀 React Native Boilerplate And Code format - July 2019
=======================================

[![React Native](https://img.shields.io/badge/React%20Native-v0.55-blue.svg)](https://facebook.github.io/react-native/)
[![React Navigation V2](https://img.shields.io/badge/React%20Navigation-v2..0.1-blue.svg)](https://reactnavigation.org/)


React Native Boilerplate is a starting point for React Native application. This project is configured with redux, redux saga 
and redux persist. Latest version of react-navigation (3.11.0).

## Features

* [Redux](http://redux.js.org/)
* [Redux Saga](https://redux-saga.js.org/)
* [Redux Persist](https://github.com/rt2zz/redux-persist/)
* [React Navigation](https://reactnavigation.org/) 
* [Jest](https://facebook.github.io/jest/)
* [Eslint](http://eslint.org/) ([Airbnb config](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb))

## Prerequisites

* [Node](https://nodejs.org) v6.10 (it is recommended to install it via [NVM](https://github.com/creationix/nvm))
* [Yarn](https://yarnpkg.com/)
* A development machine set up for React Native by following [these instructions](https://facebook.github.io/react-native/docs/getting-started.html)

## Getting Started

1. Clone this repo, `git clone https://github.com/ileafsolutions/React-Native-CodeFormat.git <your project name>`
2. Go to project's root directory, `cd <your project name>`
3. Remove `.git` folder,  `rm -rf .git`
4. Open `package.json` and change the `name` property with your project name
5. Run `yarn` or `npm install` to install dependencies
6. Remove android contents `rm -rf android`
7. Remove ios contents `rm -rf ios`
8. Open `app.json` and change the `name` and `displayName` property with your project name
9. Run `react-native eject` to update the project name to `android` and `ios` 
10. Run `react-native link`
11. Open `index.js` and replace `'ReactNativeBoilerPlate'` by your project name
12. Start the packager with `npm start`
13. Connect a mobile device to your development machine
14. Run the test application:
  * On Android:
    * Run `react-native run-android`
  * On iOS:
    * Open `ios/YourReacTproject.xcodeproj` in Xcode
    * Hit `Run` after selecting the desired device
15. Enjoy!!!


## Contributing

**Never** commit directly on master, instead use branches and pull requests.

