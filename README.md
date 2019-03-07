## Pagination Component

This pagination component can be used any where applicable like grids etc, 
It works independent with out any dependencies 

### How to use

PaginationComponent will render different types of paginations, below props
are exposed to that you can customize as per your requirement

{number} numberOfPages: total number of pages,
{function} getCurrentPage: will return the current page index,
{number} currentPage: default page to be selected on onLoad,
{bool} showFirstLast: if true will show first and last option else no,
{number} showPages: how many pages to be rendered in UI,
{array} showText: ["First", "Back", "Next", "Last"] can pass any text for
first,last,back and next.
{string} className: can pass any string to write our own CSS,


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

