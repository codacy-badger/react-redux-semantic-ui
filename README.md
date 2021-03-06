![Build Status](https://travis-ci.org/kaigouthro/react-redux-semantic-ui.svg?branch=master)
![Dependency Status](https://david-dm.org/kaigouthro/react-redux-semantic-ui.svg?branch=master)
![devDependency Status](https://david-dm.org/kaigouthro/react-redux-semantic-ui/dev-status.svg?branch=master)

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/088181f9b9534f26a68d76ccd8b71410)](https://www.codacy.com/app/kaigouthro/react-redux-semantic-ui?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=kaigouthro/react-redux-semantic-ui&amp;utm_campaign=Badge_Grade)
[![Greenkeeper badge](https://badges.greenkeeper.io/kaigouthro/react-redux-semantic-ui.svg)](https://greenkeeper.io/)
[![CircleCI](https://circleci.com/gh/kaigouthro/react-redux-semantic-ui/tree/master.svg?style=svg)](https://circleci.com/gh/kaigouthro/react-redux-semantic-ui/tree/master)

> Graciously, and [ Officially deploying to Heroku](https://react-redux-semantic-hotplate.herokuapp.com/) for master build, check it out there. 

-----

## React Redux Universal Hot Example With Semantic UI, Feathers API, Express, and much more

THIS branch only. check main branch for their more experienced edits...
mine are more like many little iterations, not all of which are complete or perfect.
i have the build icon though, and it's got some extremely rigorous settings..

just because the build passes though, doesn't mean anything i'm working on is complete.
as i write this november 19/2018, 4 years after the originator wrote a bunch of what's below, i'm editing the creation into something else on one branch, and making mostly design edits and mild function edits to the mainline.

my version i will be stripping the components out to make it far more modular, and less of the pages will have everything coded on one sheet, but rather, i'll componentize the parts down to primal functions and pieces to be used. =) that will take time, so don't expect my offshoot branch to move functionally quickly or get commits as often as my sandboxes..  so... without further ado...

# This is the KG noob-friendly version

>> This Fork's Status. do not let it reflect on the main line. mine will be missing a few things from the main line, and have some other things more tuned to my priorities, ie: Visual design language, and system operational flow and compartmentalized organization right from the start. some things are going to be moved and organized into subfolders, including additional compatible components and themes, as well as a style-guide page built right in for the dev's like myself who want to have their cheat sheet right on hand within their own dev environent. i also plan on going through deep diving at all those deprecated dependencies and updating code through the whole project to account for newer better dependencies. it's not cool to see this project relying on a v 1.0.5 _CORE_ dependency that's out  at v. 6.0.0, meanwhile a lot of other plugins can't update to their newest versions because it would break. Lots of this project still depends on 3-4 year old dependencies, and dependencies stating very clkearly "discontinued, do not use, use this instead, since 2016"..

So.....
i'm going to update whatever i can figure out how to as a side project to this fork. i'll have one that follows and can interchange some pieces with the main branch, and then i'll work on my own branch as well, removing some of the demos, because you can always see them in the main branch, and they are complicated, and i'mk making a version with less complication and easier learning curve and faster and more stable setup by the way of not having as many working examples of full fledged systems, but have a few very simple components used in a way that makes them very easy to understand when reading the code, which will be commented fairly extensively.


---
 now, a slightly edited Forward, originally written by the OG i updated it for the 4 year time jump, from will be to was, want to, to "did"...

---
## Demo - The Original
[React Redux Semantic UI](https://react-redux-semantic-ui.shopecific.com/)

## About

This is a starter boilerplate app Erik Rasmussen pioneered, and later Kévin Berthommier and Dong Cai maintained, and improved, putting together and using the following technologies in a very crafty way to make "lightning fast." a reality.

* [Universal](https://medium.com/@mjackson/universal-javascript-4761051b7ae9) rendering
* Both a client and a seperate API server making simultaneous calls.
* [React](https://github.com/facebook/react)
* [React Router](https://github.com/reactjs/react-router)
* [Express](http://expressjs.com)
* [Feathers](http://feathersjs.com/) (based on express and websockets, fast!)
* [Passport](http://passportjs.org), [feathers-authentication](https://github.com/feathersjs/feathers-authentication) and [redux-auth-wrapper](https://github.com/mjrussell/redux-auth-wrapper) for authentication
* [Babel](http://babeljs.io) for ES6 and ES7 magic
* [Webpack](https://webpack.js.org/) for bundling
* [Webpack Dev Middleware](http://webpack.github.io/docs/webpack-dev-middleware.html)
* [Webpack Hot Middleware](https://github.com/glenjamin/webpack-hot-middleware)
* [Redux](https://github.com/reactjs/redux)'s futuristic [Flux](https://facebook.github.io/react/blog/2014/05/06/flux.html) implementation
* [Redux Dev Tools](https://github.com/reactjs/redux-devtools) for next generation DX (developer experience). Watch [Dan Abramov's talk](https://www.youtube.com/watch?v=xsSnOQynTHs). (Check the browser extension for chrome as well)
* [React Router Redux](https://github.com/reactjs/react-router-redux) Redux/React Router bindings.
* [ESLint](http://eslint.org) to maintain a consistent code style
* [redux-form](http://redux-form.com/) to manage form state in Redux
* [lru-memoize](https://github.com/erikras/lru-memoize) to speed up form validation
* [multireducer](https://github.com/erikras/multireducer) to combine single reducers into one key-based reducer
* [style-loader](https://github.com/webpack/style-loader), [sass-loader](https://github.com/jtangelder/sass-loader) and [less-loader](https://github.com/webpack/less-loader) to allow import of stylesheets in plain css, sass and less,
* [semantic-ui-react](https://github.com/Semantic-Org/Semantic-UI-React)
* [font-awesome](https://github.com/FortAwesome/Font-Awesome)
* [react-helmet](https://github.com/nfl/react-helmet) to manage title and meta tag information on both server and client
* [webpack-isomorphic-tools](https://github.com/halt-hammerzeit/webpack-isomorphic-tools) to allow require() work for statics both on client and server
* [Jest](https://facebook.github.io/jest/) to allow writing unit tests for the project.

These Heroes cobbled this together from a wide variety of similar "starter" repositories. As I (KG) post this in November 2018, i think back to how forward thinking it was back in June 2015 to have created this, all of these libraries were and still are right at the bleeding edge of web development. They may fall out of fashion as quickly as they have come into it, (KG: i doubt it) but they personally believed that this stack was the future of web development and will survive for several years. They went on building their new projects like this, and they, as well as I recommend that you do, too.

#
## [ /KG's edited forward> ] ##
#


## Features

<dl>
  <dt>Hot reload</dt>
  <dd>Enjoy the developer experience! Your saved changes to the CSS and JS are reflected instantaneously without refreshing the page ! On the server as on the client.
  Preserving the state of application on the client.</dd>

  <dt>Next generation JavaScript</dt>
  <dd>Use JSX syntax with all ES6 features, and some of ES7 (see <a href=".babelrc">.babelrc</a>).</dd>

  <dt>CSS in modules</dt>
  <dd>Write composable, modular and maintenable CSS with your components.</dd>

  <dt>Predictable state management</dt>
  <dd>Unidirectional data flow with <a href="http://redux.js.org">Redux</a> helps you write applications that behave consistently and are easy to test. On top of that, it provides a great developer experience.</dd>

  <dt>Backend API oriented services</dt>
  <dd>With <a href="http://feathersjs.com">Feathers</a> it's easy to create scalable real-time applications with services and hooks.
  <a href="https://en.wikipedia.org/wiki/Cross-cutting_concern">Cross cutting concerns</a> are an extremely powerful part of aspect oriented programming. They are a very good fit for web and mobile applications since the majority are primarily CRUD applications with lots of shared functionality. You can create before and after hooks and chain them together to create very complex processes while still maintaining modularity and flexibility.</dd>

  <dt>Authentication</dt>
  <dd><a href="http://passportjs.org">Passport</a> authentication allows you to use all the desired strategies. The connections in REST and in real time are protected in the same way with the hooks. React-router, redux and <a href="https://github.com/mjrussell/redux-auth-wrapper">redux-auth-wrapper</a> allow you to keep control in your React app.</dd>

  <dt>Progressive wep app & Offline-first</dt>
  <dd>Progressive Web Apps are user experiences that have the reach of the web, and are:<br>
Reliable - Load instantly and never show the downasaur, even in uncertain network conditions.<br>
Fast - Respond quickly to user interactions with silky smooth animations and no janky scrolling.<br>
Engaging - Feel like a natural app on the device, with an immersive user experience.<br><br>
This new level of quality allows Progressive Web Apps to earn a place on the user's home screen.</dd>

  <dt>Lazy loading & dynamic routing</dt>
  <dd>The code splitting makes the size of your main bundle almost fixed, and with react-router you can load application pieces on demand. You can send bundles to people who are only trained, such as administration.</dd>

  <dt>Universal rendering</dt>
  <dd>With the help of server side rendering the first rendering is never empty and performance is better. This is the time for example to prefetch the data.
<a href="https://github.com/halt-hammerzeit/webpack-isomorphic-tools">Webpack-isomorphic-tools</a> to allow require() work for statics both on client and server.</dd>

  <dt>SEO</dt>
  <dd>This project supports SEO for search engines even without support indexing of JavaScript content, thanks to server-side rendering.</dd>
</dl>

## Installation

```bash
yarn install
```

## Running Dev Server

```bash
yarn dev
```

The first time it may take a little while to generate the first `webpack-assets.json` and complain with a few dozen `[webpack-isomorphic-tools] (waiting for the first Webpack build to finish)` printouts, but be patient. Give it 30 seconds.

### Using Redux DevTools

[Redux Devtools](https://github.com/gaearon/redux-devtools) are enabled by default in development.

- <kbd>CTRL</kbd>+<kbd>H</kbd> Toggle DevTools Dock
- <kbd>CTRL</kbd>+<kbd>Q</kbd> Move DevTools Dock Position
- see [redux-devtools-dock-monitor](https://github.com/gaearon/redux-devtools-dock-monitor) for more detailed information.

If you have the [Redux DevTools chrome extension](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd) installed it will automatically be used on the client-side instead.

If you want to disable the dev tools during development, set `__DEVTOOLS__` to `false` in `/webpack/dev.config.js`.
DevTools are not enabled during production by default.

## Building and Running Production Server

```bash
npm run build
npm run start
```

## Demo

A demonstration of this app can be seen [here](http://react-redux-semantic-ui.shopecific.com/),

## Explanation

What initially gets run is `bin/server.js`, which does little more than enable ES6 and ES7 awesomeness in the server-side node code. It then initiates `server.js`. In `server.js` we proxy any requests to `/api/*` to the API server, running at `localhost:3030`. All the data fetching calls from the client go to `/api/*`. Aside from serving the favicon and static content from `/static`, the only thing `server.js` does is initiate delegate rendering to `react-router`. At the bottom of `server.js`, we listen to port `3000` and initiate the API server.

#### Routing and HTML return

The primary section of `server.js` generates an HTML page with the contents returned by `react-router`. First we instantiate an `ApiClient`, a facade that both server and client code use to talk to the API server. On the server side, `ApiClient` is given the request object so that it can pass along the session cookie to the API server to maintain session state. We pass this API client facade to the `redux` middleware so that the action creators have access to it.
You can also use `app` for RESTful calls to api.

Then we perform [server-side data fetching](#server-side-data-fetching), wait for the data to be loaded, and render the page with the now-fully-loaded `redux` state.

The last interesting bit of the main routing section of `server.js` is that we swap in the hashed script and css from the `webpack-assets.json` that the Webpack Dev Server – or the Webpack build process on production – has spit out on its last run. You won't have to deal with `webpack-assets.json` manually because [webpack-isomorphic-tools](https://github.com/halt-hammerzeit/webpack-isomorphic-tools) take care of that.

We also spit out the `redux` state into a global `window.__data` variable in the webpage to be loaded by the client-side `redux` code.

#### Server-side Data Fetching

The [redial](https://www.npmjs.com/package/redial) package exposes an API to return promises that need to be fulfilled before a route is rendered. It exposes a `<ReduxAsyncConnect />` container, which wraps our render tree on both [server](https://github.com/bertho-zero/react-redux-universal-hot-example/blob/master/src/server.js) and [client](https://github.com/bertho-zero/react-redux-universal-hot-example/blob/master/src/client.js). More documentation is available on the [redial](https://www.npmjs.com/package/redial) page.

#### Client Side

The client side entry point is reasonably named `client.js`. All it does is load the routes, initiate `react-router`, rehydrate the redux state from the `window.__data` passed in from the server, and render the page over top of the server-rendered DOM. This makes React enable all its event listeners without having to re-render the DOM.

#### Redux Middleware

The middleware, [`clientMiddleware.js`](https://github.com/bertho-zero/react-redux-universal-hot-example/blob/master/src/redux/middleware/clientMiddleware.js), serves two functions:

1. To allow the action creators access to the client API facade. Remember this is the same on both the client and the server, and cannot simply be `import`ed because it holds the cookie needed to maintain session on server-to-server requests.
2. To allow some actions to pass a "promise generator", a function that takes the API client and returns a promise. Such actions require three action types, the `REQUEST` action that initiates the data loading, and a `SUCCESS` and `FAILURE` action that will be fired depending on the result of the promise. There are other ways to accomplish this, some discussed [here](https://github.com/reactjs/redux/issues/99), which you may prefer, but to the author of this example, the middleware way feels cleanest.

#### Redux Modules... *What the Duck*?

The `src/redux/modules` folder contains "modules" to help
isolate concerns within a Redux application (aka [Ducks](https://github.com/erikras/ducks-modular-redux), a Redux Style Proposal that I came up with). I encourage you to read the
[Ducks Docs](https://github.com/erikras/ducks-modular-redux) and provide feedback.

#### Getting data and actions into components

To understand how the data and action bindings get into the components – there's only one, `InfoBar`, in this example – I'm going to refer to you to the [Redux](https://github.com/gaearon/redux) library. The only innovation I've made is to package the component and its wrapper in the same js file. This is to encapsulate the fact that the component is bound to the `redux` actions and state. The component using `InfoBar` needn't know or care if `InfoBar` uses the `redux` data or not.

#### Images

Now it's possible to render the image both on client and server. Please refer to issue [#39](https://github.com/erikras/react-redux-universal-hot-example/issues/39) for more detail discussion, the usage would be like below (super easy):

```javascript
let logoImage = require('./logo.png');
```

#### Styles

This project uses [local styles](https://medium.com/seek-ui-engineering/the-end-of-global-css-90d2a4a06284) using [css-loader](https://github.com/webpack/css-loader). The way it works is that you import your stylesheet at the top of the `render()` function in your React Component, and then you use the classnames returned from that import. Like so:

```javascript
render() {
const styles = require('./App.scss');
...
```

Then you set the `className` of your element to match one of the CSS classes in your SCSS file, and you're good to go!

```jsx
<div className={styles.mySection}> ... </div>
```

#### Alternative to Local Styles

If you'd like to use plain inline styles this is possible with a few modifications to your webpack configuration.

**1. Configure Isomorphic Tools to Accept CSS**

In `webpack-isomorphic-tools.js` add **css** to the list of style module extensions

```javascript
    style_modules: {
      extensions: ['less','scss','css'],
```

**2. Add a CSS loader to webpack dev config**

In `dev.config.js` modify **module loaders** to include a test and loader for css

```javascript
  module: {
    loaders: [
      { test: /\.css$/, loader: 'style-loader!css-loader'},
```

**3. Add a CSS loader to the webpack prod config**

You must use the **ExtractTextPlugin** in this loader. In `prod.config.js` modify **module loaders** to include a test and loader for css

```javascript
  module: {
    loaders: [
      { test: /\.css$/, loader: ExtractTextPlugin.extract('style-loader', 'css-loader')},
```

**Now you may simply omit assigning the `required` stylesheet to a variable and keep it at the top of your `render()` function.**

```javascript
render() {
require('./App.css');
require('aModule/dist/style.css');
...
```

**NOTE** In order to use this method with **scss or less** files one more modification must be made. In both `dev.config.js` and `prod.config.js` in the loaders for less and scss files remove

1. `modules`
2. `localIdentName...`

Before:
```javascript
{ test: /\.less$/, loader: 'style!css?modules&importLoaders=2&sourceMap&localIdentName=[local]___[hash:base64:5]!autoprefixer?browsers=last 2 version!less?outputStyle=expanded&sourceMap' },
```
After:
```javascript
{ test: /\.less$/, loader: 'style!css?importLoaders=2&sourceMap!autoprefixer?browsers=last 2 version!less?outputStyle=expanded&sourceMap' },
```

After this modification to both loaders you will be able to use scss and less files in the same way as css files.

#### Unit Tests

The project uses [Jest](https://facebook.github.io/jest/) to run your unit tests.

To run the tests in the project, just simply run `npm test` if you have `Chrome` installed, it will be automatically launched as a test service for you.

## Deployment on Heroku

To get this project to work on Heroku, you need to:

1. Remove the `"PORT": 8080` line from the `betterScripts` / `start-prod` section of `package.json`.
2. `heroku config:set NODE_ENV=production`
3. `heroku config:set NODE_PATH=./src`
4. `heroku config:set NPM_CONFIG_PRODUCTION=false`
  * This is to enable webpack to run the build on deploy.

The first deploy might take a while, but after that your `node_modules` dir should be cached.

## Deployment on your server with PM2 (optional)
1. Install PM2 `npm install pm2@latest -g`
2. Run `sh deploylment/deploy.sh` (please check deploy.sh for comments)

## FAQ

This project moves fast and has an active community, so if you have a question that is not answered below please file an issue.


## Roadmap

Although this isn't a library, we recently started versioning to make it easier to track breaking changes and emerging best practices.

* [Inline Styles](docs/InlineStyles.md) - CSS is dead

## Contributing

I am more than happy to accept external contributions to the project in the form of feedback, bug reports and even better - pull requests :)

If you would like to submit a pull request, please make an effort to follow the guide in [CONTRIBUTING.md](CONTRIBUTING.md).

---
Thanks for checking this out.

Created by: Erik Rasmussen, [@erikras](https://twitter.com/erikras)

Maintened by:
- Kévin Berthommier, [@bertho-zero](https://github.com/bertho-zero)
- Dong Cai, [@dongcai](https://github.com/dongcai)
---
>   This version by [Kai Gouthro](https://github.com/kaigouthro)
