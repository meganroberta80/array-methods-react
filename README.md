# Lab: Array Methods with React

This lab will give you a chance to practice looping through data in a React App.

![loops in the sky](./images/sky-loop.jpg)

We'll be using JavaScript's **[fancy array methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)**. These give us a lot of power to manipulate data in arrays and can be a lot of fun once you get the hang of it!

You'll mainly be using these three.
- [Map method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
- [Filter method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- [Find method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)

Other use array iterator methods
- [For Each](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
- [Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
- [Includes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)
- [Every](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)

## Setup

To set up the activity
- Clone down this repo to your local machine.
- Once cloned down cd into this repo with `cd array-methods-react`.
- Run `npm install` to install all the necessary packages.
- Run `npm start` to start of the app in the browser.

## Familiarize Yourself w/ the Code

Take a look at the `./src/planetData.js` file. The file contains an array of planet data.

This planet data is pulled into `App.js`.

At the moment the App component is set up to render an array of `<p>` tags, one for each planet in the  `planetData` array.

## Solving Challenges

We've solved the first challenge for you as an example.

When ready, go ahead and comment out the `renderPlanets()` function for Challenge #1 and uncomment the function for Challenge #2.

Each challenge will have you display a different set of data to the page. For each challenge write some code using one of the JavaScript array iterator methods to return some JSX and displayed the desired output to the page.

Do your best to work through each challenge. If you've been stuck on any particular challenge for more than 20 minutes take a peek at the solution found in the [solutions.md](./solutions.md) file.