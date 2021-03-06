# Portfolio Site

### Idea

Originally, I wanted to build a new portfolio site and do so quickly. I wanted it to be a gateway to see my personal projects, but figured I'd at least make it in React. After spending too much time on simple stuff while flip-flopping on a style, I decided to keep the style simple. While googling around for something to spark my imagination, it struck me that I should just make a google-like front-end clone. It could act as wireframes and would definitely stand out. Once I decided this, I just kept going with the idea and decided to make it its own full stack project, complete with a functional search that would allow one to search through my entire site. It would also allow me to show off skills without hoping someone clicks on a certain project that I have listed. I could make it big enough to create some modular features but not require time spent testing out different transitions or going back and forth on CSS layouts.

### Current State of the Portfolio and Plans for Future

For now, it is only a React (with CRA) front-end. The projects are all in a JSON blob that will eventually be the data stored in a database. It is a work in progress, but here is what I hope to add in the near future:

1. More modular features
2. The "data" in SQL or Mongo database. This data will be anything I want to be searchable and/or editable.
3. Add an admin panel or even a CMS that I can update these projects through.
4. GraphQL with Apollo Client - I've done a lot of work with Apollo queries and mutations, but want to be more familiar with writing GraphQL resolvers and testing them
5. Fully-functional Search feature that will return different results after each key press based on the input text matching keywords associated with each project
6. Fully cover the project with effective unit tests and integration tests

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

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
