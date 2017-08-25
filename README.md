# hello-world-react !
**Hello World React** is a simple starter application built using [React](https://facebook.github.io/react/). It is configured using [Webpack](https://webpack.github.io/docs/).

The purpose of this application is to demonstrate the ease with which an ReactJS SPA can be setup with Webpack. This can also be used as a **starter project** for any ReactJS project as it is not opinionated with any design patterns, architecture or extra third-party libraries.

## Setup
* `git https://github.com/mario-christopher/hello-world-react.git`
* `cd hello-world-react`
* `npm install`
* `npm run start`
* Browse to http://localhost:8080 *( tested on Chrome and IE.11 ).*

For production build, edit file `webpack.config.js` and replace

`module.exports = require('./config/webpack.dev.js');`

with

`module.exports = require('./config/webpack.prod.js');`

Then run `npm run build` in the terminal. You could also code for checking `process.env.NODE_ENV` in `webpack.config.js` and use the appropriate config file.


##  Application features:

* Uses the stable build for ReactJS 15.6.x
* Webpack configured for Dev and Prod environments.
* Can be used as a Starter project for any ReactJS based client.
* Configured to use ES6 features.
* Uses polyfills to cover most modern browsers.

##   License

Shared under MIT License.