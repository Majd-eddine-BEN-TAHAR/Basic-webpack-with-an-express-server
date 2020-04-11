# Basic Webpack Setup With Express Server

The goal of this repo is be an example of a basic but functional app built on Webpack.

## What cover the repo

- Transpiling Sass files to one CSS file using Webpack
- CSS Autoprefixer
- Transpile Javascript ES6 to ES5 code compatible for older browsers using Babel.
- Moving images from src folder to dist folder when running the app
- Express Server
- service-workers for offline capability
- Testing with Jest

## Get Up and Running

Fork this repo, then clone it down to your computer:

- cd into your new folder and type:

```
npm install
```

- To start the express server with production on localhost:8085 type :

```
npm start
```

- To lunch only the server type :

  ```
  npm run launch-server
  ```

- To start the webpack dev server type :

```
npm run build-dev
```

- To generate a dist folder for production type:

```
npm run build-prod
```

- To run tests with Jest type:

```
npm test
```

## Built With

- [HTML]()Markup Language
- [Sass](https://sass-lang.com/documentation) - CSS Framework
- [Webpack](https://webpack.js.org/concepts/) - Asset Management
- [Babel](https://babeljs.io/) - JavaScript Compiler
- [Node.js](https://nodejs.org/en/) - JavaScript Runtime
- [Express.js](https://expressjs.com/) - Server Framework for Node.js
- [Jest](https://jestjs.io/) - Testing suit
- [Service Workers](https://developers.google.com/web/fundamentals/primers/service-workers) - For offline capability

​

## License

This project is licensed under the MIT License
