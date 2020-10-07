# [WEBCHANNEL](https://webchannel.dev/)

## Preview

**[View Live Preview](https://webchannel.dev/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/AJ-7885/webchannel/edit/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/webchannel.dev.svg)](https://www.npmjs.com/package/webchannel.dev)
[![Build Status](https://api.travis-ci.org/AJ-7885/webchannel.svg?branch=master)](https://travis-ci.org/AJ-7885/webchannel)
[![dependencies Status](https://david-dm.org/AJ-7885/webchannel.svg)](https://david-dm.org/AJ-7885/webchannel)
[![devDependencies Status](https://david-dm.org/AJ-7885/webchannel/dev-status.svg)](https://david-dm.org/AJ-7885/webchannel?type=dev)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/67c86c7bd116499b8a1c1d6865d55514)](https://www.codacy.com/app/Ali-7885/webchannel?utm_source=github.com&utm_medium=referral&utm_content=AJ-7885/webchannel&utm_campaign=Badge_Grade)

This project was bootstrapped with [Create React HomePage](https://github.com/facebook/create-react-app).
hae
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

You can learn more in the [Create React HomePage documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web HomePage

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify

# Rules

-   The Atomic Design should have a file of <b>variables</b> and it must be imported by each component;
-   The <b>atoms</b> should be written without margins and positions;
-   Only the <b>molecules</b> and <b>organisms</b> can set the positions of atoms, but these stacks - can’t have any styles of margins and positions;
-   <b>Templates</b> have only one function: to set the grid of pages but never positions of specific components;
-   <b>Pages </b>render the components with a template defined and it’s here that the <b>Atomic Design</b> will be connected to the rest of the application;
