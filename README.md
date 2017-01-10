## ![CF](https://i.imgur.com/7v5ASc8.png) Lab 07: NodeJS and NPM

Today is your introduction to server-side development using NodeJS and NPM (Node Package Manager). We're also using a very common routing utility for Node called ExpressJS, which allows the ability to define our own URI's and effect functionality upon navigating to each of those specified routes.

Your lab today will require you to initiate a new NPM project, install ExpressJS into our app, and complete the TODOs in our new `server.js` file.

## TODOs: MVP
1. Move everything into a new root-level directory in the project called `public`
1. `touch` a `server.js` file
1. Initiate the project with NPM and create a `package.json` file.
1. Install ExpressJS, and ensure that it's been saved as a dependency in the `package.json` file.
1. Complete each of the TODOs in the `server.js` file.
1. Create a route and callback that will serve up the `new.html` page via a separate URI.
1. Run the server using `node server` and ensure that your app functions correctly.

## Stretch Goals:
1. Create a ***404*** route to handle any requests other than `index.html` or `new.html`, and deliver a 404 status message or customized page to those invalid requests.
