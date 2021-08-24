# Array Methods with React

This lab will give you a chance to practice the JavaScript array methods in the context of a React app.

## Setup

To set up the activity
- Clone down this repo to your local machine.
- Once cloned down cd into this repo with `cd array-methods-react`.
- Run `npm install` to install all the necessary packages.
- Run `npm start` to start of the app in the browser.

## Familiarize Yourself w/ the Code

Take a look at the `./src/planetData.js` file. The file contains an array of planet data.

This planet data is pulled into `App.js`.

Inside of `App.js` you'll find our App component. The render method of the App component all the way on the bottom of the file is rendering out an `<h1>` and calls `this.renderPlanets()`. `renderPlanets()` at the moment renders an array of `<p>` tags, showing each planet's name from the planetData array.

## Solving Challenges

We've solved the first challenge for you as an example.

When ready, go ahead and comment out the `renderPlanets()` function for Challenge #1 and uncomment the function for Challenge #2.

For each challenge write some code to solve each particular challenge. For each challenge you'll be returning some JSX that will get outputted into the browser.

Do your best to work through each challenge. If you've been stuck on any particular challenge for more than 20 minutes take a peek at the solution found in the [solutions.md](./solutions.md) file.