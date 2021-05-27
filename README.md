To start:

1. Find & Replace `TOP_LEVEL_DOMAIN` with your top level domain (IE: `com`)
2. Find & Replace `PROJECT_NAME` with the name of your project

# Pre-Requisites

1. NodeJS
2. Yarn

# Running app

1. `yarn`
2. `yarn run start`

# Building

1. `yarn run build`

# Features

1. Create React App
2. Tailwind
3. Cypress
4. Storybook
5. Eslint
6. Prettier running as a lint rule

# Environment variables
### ```REACT_APP_ENVIRONMENT```
Not the same thing as ```process.env.NODE_ENV```, set this so that Sentry knows the difference between develop, staging and productionenvironments.
As far as ```process.env.NODE_ENV``` is concerned, run build meansthat it's production.


### ```REACT_APP_SENTRY_DSN```
DSN from sentry.
