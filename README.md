# Typescript Eslint Prettier Boilerplate

This is a boilerplate project for a Node.js project with TypeScript, ESLint, and Prettier. It provides a starting point for developing TypeScript applications with a standardized code style and linting configuration.

## Project Structure

The project structure is as follows:

- `src/index.ts`: The entry point of the application with a simple "Hello World" console log statement.
- `.eslintrc.json`: ESLint configuration file specifying linting rules and plugins for TypeScript.
- `.prettierrc.json`: Prettier configuration file specifying code formatting rules.
- `package.json`: NPM package configuration file containing project metadata and script commands.
- `tsconfig.json`: TypeScript compiler configuration file defining compiler options and file inclusion/exclusion.

## Available Scripts

In the project directory, you can run the following scripts:

- `npm start`: Transpiles TypeScript files using `tsc` and executes the compiled `dist/index.js` file using Node.js.
- `npm run dev`: Uses `ts-node-dev` to run the TypeScript files directly without compilation for development purposes.
- `npm run dev:watch`: Similar to `npm run dev`, but automatically restarts the server on file changes.
- `npm run lint`: Runs ESLint to check for linting issues in both JavaScript and TypeScript files.
- `npm run lint:fix`: Runs ESLint with the `--fix` flag to automatically fix linting issues in JavaScript and TypeScript files.
- `npm run format`: Formats JavaScript and TypeScript files using Prettier.

## Getting Started

1. Clone the repository `git clone https://github.com/JoShMiQueL/typescript-eslint-prettier-boilerplate`.
2. Install the dependencies using `npm install`.
3. Run the app using `npm run dev`.
4. Make changes to the `src/index.ts` file or add new files as needed for your project.

> **_NOTE:_** The code will be automatically transpiled and executed on save during development. Additionally you can run `npm run dev:watch` if you want the app to restart when you make a change to the code.

## Configuration Files

The project configuration files can be found at the following links:

[tsconfig.json](https://gist.github.com/JoShMiQueL/58b2825647f54f00b07dc84e3d0e7bcd)\
[.eslintrc.json](https://gist.github.com/JoShMiQueL/c3a3bdd7a4f11e84207d891e80d13426)\
[.prettierrc.json](https://gist.github.com/JoShMiQueL/017a50db271d0fbe2bb4203b1729d763)

## Linting and Formatting

- Run `npm run lint` to check for linting issues in your JavaScript and TypeScript files.
- Run `npm run lint:fix` to automatically fix linting issues in your JavaScript and TypeScript files.
- Run `npm run format` to format your JavaScript and TypeScript files using Prettier.

## License

This project is licensed under the ISC License. See the LICENSE file for details.
