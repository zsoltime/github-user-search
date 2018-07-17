# GitHub User Search

## User Stories

- [ ] As a user, I can see a search form on page load, so I can search for GitHub users by their username.
- [ ] As a user, I can see a list of matching users after I submit a username in the search form.
- [ ] As a user, I can click on any of the listed users, so I can see their profile.
- [ ] As a user, I can see the following info on the user profile page:
  - [ ] name
  - [ ] avatar
  - [ ] tagline
  - [ ] location
  - [ ] website
  - [ ] number of followers
  - [ ] number of repos
  - [ ] number of users followed by the user
  - [ ] most recent repositories

## Tools Used

- [React.js](https://facebook.github.io/react/) library
- [Redux](https://github.com/reduxjs/redux) state container
- [React router](https://github.com/ReactTraining/react-router)
- [Webpack](https://webpack.js.org/) module bundler
- [Babel.js](https://babeljs.io/) compiler
- [ESLint](http://eslint.org/) linter with [Airbnb's JS config](https://github.com/airbnb/javascript)
- [Sass](http://sass-lang.com/) preprocessor with PostCSS' [Autoprefixer](https://github.com/postcss/autoprefixer)

### Tests

- [Jest](https://facebook.github.io/jest/) test runner
- [Enzyme](http://airbnb.io/enzyme/) testing utilities for React

## Install and Build

##### Clone this repo

```bash
git clone https://github.com/zsoltime/github-user-search.git
cd github-user-search
```

#### Install dependencies

```bash
npm install
```

#### Create a `.env` file

You can find a `.env.example` file in the root directory as a starting point. You can copy the content of this file to `.env` and add your own values.

```bash
touch .env
```

#### Run the React app in development mode

The page will automatically reload if you make changes to the code.

```bash
npm start
```

#### Run tests

Runs the test watcher in an interactive mode.

```bash
npm test
```

#### Build production bundle

It builds production bundle, uglifies JS, minifies CSS.

```bash
npm run build
```

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).
