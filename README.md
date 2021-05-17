# A [NextJS](https://nextjs.org/) template with typescript, tailwindcss and storybook support

> The configuration of NextJS, TailwindCSS and Storybook
> 👉 So we have decided to make this template public 🎉

This project was bootstrapped with [npx create-next-app](https://nextjs.org/learn/basics/create-nextjs-app/setup) and we have added support for:

- ✅ [Typescript](https://www.typescriptlang.org/)
- ✅ [Taillwindcss](https://www.tailwindcss.com)
- ✅ [Storybook](https://storybook.js.org/)
- ✅ [Jest](https://jestjs.io/)
- ✅ [Import SVG as React Component (SVGR)](https://react-svgr.com/)

You are welcome to contribute to this project to make it better.

## To use this template:

- clone it
- remove the .git folder
- git init .
- git add .
- git commit -m "First commit"

## Install all the dependencies

### 👉 `yarn install`

## Available Scripts

In the project directory, you can run:

### 👉 `yarn dev`

**Results:**

```bash
ready - started server on http://localhost:3000
   ✅ purgeEnabled=false

event - compiled successfully
event - build page: /next/dist/pages/_error
wait  - compiling...
event - compiled successfully
event - build page: /
wait  - compiling...```

Run the project in the dev mode.
````

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### 👉 `yarn storybook`

Runs storybook.

Open [http://localhost:6006](http://localhost:6006) to view it in the browser.

### 👉 `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

> If you get an error that contained this line:

Use this command:

`brew install watchman`

### 👉`yarn build`

Builds the app for production to the `.next` folder.\
It correctly bundles NextJS in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!



See the section about [deployment](https://nextjs.org/docs/deployment) for more information.

### 👉`yarn start`

Starts a server with the output for the `yarn build` command.

`yarn build` must be executed before to use this command.

### 👉`yarn export`

Export the output of the `yarn build` command execution to the `./out` directory.

`yarn build` must be executed before to use this command.

### 👉`npx serve ./out`

To launch a **static server** from the `./out` directory. This command can be useful to control the outcome of `yarn export`.

`yarn build` and `yarn export` must be executed before to use this command.

## Learn More

You can learn more in the [NextJS documentation](https://nextjs.org/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

To learn how to develop UIs with component and design systems with Storybook, check out the [Learn Storybook documentation](https://www.learnstorybook.com/)
