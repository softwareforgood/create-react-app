# Software for Good's react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app) plus a custom set of packages commonly included at Software for Good.

## Motivation

CRA does an excellent job building and maintaining project scaffolding saving devs hours of hassle setting up build tools and configuration. However, we can build on this in an opinionated way to start projects in a consistent and recognizable manner.

## Getting Started

```javascript
npx create-react-app my-app --scripts-version @softwareforgood/sfg-react-scripts
```

To also include our project template,

```javascript
npx create-react-app test-app --scripts-version @softwareforgood/sfg-react-scripts --template @softwareforgood/react-for-good
```

## Staying up to date

When you update `@softwareforgood/sfg-react-scripts` you get the latest `react-scripts` release plus included versions of all the packages below. You will not need to maintain these package versions downstream in your projects.

```javascript
yarn add --exact @softwareforgood/sfg-react-scripts@<version number>
```

## Customizations

| Package                                                                               | Role                                                      |
| ------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [Axios](https://github.com/axios/axios)                                               | Promise based HTTP client for the browser and node.js     |
| [FontAwesome](https://fontawesome.com/)                                               | Icons                                                     |
| [Moment](https://momentjs.com/)                                                       | Date/Time library                                         |
| [Node Sass](https://github.com/sass/node-sass)                                        | Node bindings for SASS                                    |
| [Prettier](https://prettier.io/)                                                      | Code formatting                                           |
| [Prop Types](https://github.com/facebook/prop-types)                                  | Runtime type checking for React props and similar objects |
| [React Redux](https://react-redux.js.org/)                                            | React bindings for Redux                                  |
| [React Router](https://reacttraining.com/react-router/web/guides/quick-start)         | Client-side routing                                       |
| [React Testing Library](https://testing-library.com/docs/react-testing-library/intro) | Test library                                              |
| [React Testing Library/jest-dom](https://github.com/testing-library/jest-dom)         | Additional matcher library for RTL                        |
| [React Testing Library/react-hooks](https://github.com/testing-library/react-hooks)   | Additional hook testing library for RTL                   |
| [React Testing Library/user-event](https://github.com/testing-library/user-event)     | Additional event simulator library for RTL                |
| [Redux](https://redux.js.org/)                                                        | State Container                                           |
| [Redux Toolkit](https://redux-toolkit.js.org/)                                        | Opinionated toolset for Redux                             |
|                                                                                       |
