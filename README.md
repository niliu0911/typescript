# React Typescript Webpack

- React
- Jasmine
- Karma
- SASS
- Typescript
- Webpack
- Webpack Development Server

#### Prerequisites
- `node >=5.12`

#### Quick Start
```shell
$ npm install
$ npm run typings
$ npm start
```

Usage
-----

|Script|Description|
|---|---|
|`npm start`|Start webpack development server @ `localhost:3000`|
|`npm run build`|Lint, test, and build the application to `./target`|
|`npm run lint`|Lint `.ts` and `.js` files|
|`npm run lint:js`|Lint `.js` files with eslint|
|`npm run lint:ts`|Lint `.ts` files with tslint|
|`npm run server`|Start express server @ `localhost:3000` to serve built artifacts from `./target` (must run `npm run build` first)|
|`npm test`|Run unit tests with Karma and Jasmine|
|`npm run test:watch`|Run unit tests with Karma and Jasmine; watch for changes to re-run tests|
|`npm run typings`|Install ambient typings|
|`npm version`|Bump package.json version, generate CHANGELOG.md, git commit and tag (see [npm version](https://docs.npmjs.com/cli/version))|

#### Demo

The Demo is development by Backbone.