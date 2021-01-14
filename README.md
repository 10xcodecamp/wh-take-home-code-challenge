# Take-home Code Challenge

:wave: Welcome to \_\_\_\_\_\_\_\_\_'s Front End Coding Challenge! This challenge is to showcase your knowledge of front-end web development with React.

There are two versions of this test:

1. Front End Engineer
2. Senior Front End Engineer

Complete whichever one you have been directed to take.

We will build a simple SPA, called **Episode Switcher**, that shows your ability to work with data on the front end. Please code in a [functional / declarative style](https://www.freecodecamp.org/news/imperative-vs-declarative-programming-difference/). Though `for` loops are very fast, for the purposes of this challenge, please avoid using `for`, `forEach`, `for...in`, and `for...of`, and instead use functional array methods. Your app should not 404 or crash, so test everything.

# 📼 [Watch a video of the app here.](https://www.youtube.com/watch?v=w82Ae6JZrv0)

## 🛑 Important

Use the following API endpoint to get a TV show and all its episodes in 1 request. (Replace `showId` with whatever id you want to get.) See [Embedding](https://www.tvmaze.com/api#embedding) in the TV Maze documentation.

```js
const url = `http://api.tvmaze.com/shows/${showId}?embed=episodes`;
```

## 🤺 Front End Engineer Challenge

Use [Create React App](https://create-react-app.dev/) and the [TVmaze API](https://www.tvmaze.com/api). Use [Bootstrap 4](https://getbootstrap.com/) or [React-Bootstrap](https://react-bootstrap.github.io/) to make your app look like the demo, though looks come second to functionality. You may use either Class Components or React Hooks.

## 🏂 Senior Front End Engineer Challenge

Use [Create React App](https://create-react-app.dev/), [TypeScript](https://www.typescriptlang.org/), [Bootstrap 4](https://getbootstrap.com/), and the [TVmaze API](https://www.tvmaze.com/api). Use React Hooks instead of Class Components. Do not mutate the values of objects or arrays and don't make shallow or deep copies of them—use [Immer](https://immerjs.github.io/immer/docs/introduction) to keep your values immutable. Never use the TypeScript `any` type. Include unit tests for your functions and component tests for your React components.

## 🚀 Submitting Your Solution

Submit a link to your Github repo. In the README include a link to a live version of the app deployed to Surge, Heroku, or another hosting service you choose.

**This should take you no longer than 1 week from the time you received it.**

## 🪂 Test Cases

You should make sure all TV shows load and display properly. We will test at least these shows:

```
Simpsons
Trains
Border Patrol
Blobs
Good Wife
Golfing World
Wedding Central
```

### 🤞 Good luck!
