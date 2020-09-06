# react-cypress-cucumber-template

This template provides setup for `cypress` and `cypress-cucumber-preprocessor`

The template was created with `create-react-app` and two dev dependencies. Here are the steps to replicate the template:

- `npx create-react-app react-cypress-cucumber-template`
- `cd react-cypress-cucumber-template`
- `npm install --save-dev cypress`
- `npm install --save-dev cypress-cucumber-preprocessor`

## How to run integration tests

- Clone this repo and run `npm install`
- Make sure that the development server is running on http://localhost:3000
  - You can do this by running `npm run start`
- Once the application is running you can then start cypress with commands below:
  - `npm run cy:headless` - this will run features in Electron headlessly i.e., in command line only.
  - `npm run cy:browser` - this will run features in Electron by opening it up. This also allows to inspect feature steps and debug.
