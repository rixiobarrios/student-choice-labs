[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Advanced Topics in React

Developers have a choice between three advanced topics in React. Pick one of the
three topics listed below and spend the lab period learning about that topic.

## Prerequisites

- React and Components.
- Working with State and Props.
- Building a MERN app.

## Instructions

1. Pick one of the three topics listed below.
1. Work through the lesson on that topic, completing all the exercises.
1. Update your MERN lab submission with what you learned.
1. Post an issue on this repository with a link to your MERN app.

You'll pick one of the three topics listed below and spend time learning it. Once you've worked through the provided lesson and exercises, update your MERN app with what you've learned. By that we mean, if you study testing with Jest and Enzyme, add tests to your MERN app; if you study authentication, add authentication to your MERN app; if you study Redux, add Redux to your MERN app.

At the end of the lab period, post an issue on this repository with a link to your MERN app.

## Topics

### 1. [Testing with Jest](https://git.generalassemb.ly/dc-wdi-react-redux/testing-in-react-with-jest-enzyme)

Jest and Enzyme are tools for writing and running automated tests on your React
components. As your app grows, it will become difficult (if not impossible) to
manually test your components. Having automated tests means you wont have to!

### 2. [Redux](https://git.generalassemb.ly/dc-wdi-react-redux/react-redux)

Redux is a state management solution for React. Rather than manage your state
inside your react compeonts, you'll manage it all within Redux. If you have a
lot of state (i.e. your app is fairly large) or your state is complicated, Redux
provides strict guidelines and a simple interface that alleviates the pain of
managin state.

### 3. [Authentication](https://git.generalassemb.ly/dc-wdi-react-redux/react-jwt-authentication)

Authentication with JSON Web Tokens lets you authenticate requests to your
Express back-end from a React front-end. It works similarly to using Passport with Sessions.

## Requirements

### Testing with Jest

Submit your MERN app with full test coverage (every component has tests written
for it). Create a coverage report using the `--coverage` flag.

#### Bonus

Research End-to-End (e2e) testing and implement it.

*Hint: [Puppeteer](https://github.com/GoogleChrome/puppeteer) is a good tool for implementing e2e testing.*

### Redux

Transition all state in your application to be managed by Redux. For this one, use static data as your state (i.e. not from your API)

#### Bonus

Switch from static data to data from your back-end.

### Authentication

Make it so users can sign up and sign in and only authenticated users can perform CRUD on your model.

#### Bonus

Integrate your JWT authentication with React-Router, so that only authenticated users can visit certain pages in your React front-end.

## [License](LICENSE)

1. All content is licensed under a CC­BY­NC­SA 4.0 license.
1. All software code is licensed under GNU GPLv3. For commercial use or
   alternative licensing, please contact legal@ga.co.
