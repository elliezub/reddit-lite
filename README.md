# Reddit Lite

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), using the [Redux](https://redux.js.org/) and [Redux Toolkit](https://redux-toolkit.js.org/) template.

The project features a Reddit client that uses the unofficial Reddit API to display posts and topics generated by Reddit users. 

You can [view a demo of Reddit Lite here.](https://adamturner-reddit-lite.netlify.app/)

## Features

1. Gets posts from the Reddit API - users can select Subreddits on a sidebar or select box on mobile which will serve a number of posts from those topics. 

2. View post metadata and comments - each post displays the author, how long ago it was posted and number of comments. Users can also click the comment button (speech bubble) to load a selection of comments for each post. 

3. Search - includes search functionality that filters posts down with terms that match items within the active sub reddit title. 

## Future Enhancements

1. Individual post view - render the whole page as an individual post when the post is clicked in the initial view.

2. Testing with Jest and Enzyme - unit tests.

3. Styling improvements - UI for navigation could be improved or less cluttered.

4. Add functionality to the up or down vote icons.

5. Include GIF, video and gallery carousel type media. Some posts show no content as these file types are unhandled.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).