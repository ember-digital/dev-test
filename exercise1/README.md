# Exercise 1: Visualising Compensation and Benefits

_**TIMEBOX:**_    1-2 hours - max!

_**ENVIRONMENT:**_ node / yarn / npm

_**LANGUAGES:**_
- TypeScript or JavaScript

_**FRAMEWORKS:**_
- [Expo](https://expo.io/), [React Native](https://reactnative.dev/) or [React](https://reactjs.org/docs/getting-started.html)
- [Next.js](https://nextjs.org/) or [Express](https://expressjs.com/)
- [Prisma](https://www.prisma.io/docs/getting-started/quickstart-typescript) (optional)
- [React Native Testing Library](https://testing-library.com/docs/react-native-testing-library/intro/) / [Jest](https://jestjs.io/) (both optional)

_**TECHNOLOGY:**_ Web and/or Mobile

_**TESTS:**_ optional

_**DOCS:**_ mandatory

# Overview

This coding exercise is to implement the best possible solution _within the allotted time_.

Ideally your solution will have some way to run locally and visualise the results so we can fully analyse the experience (and not just look at the source code).

Feel free to include some screenshots in your repo as this may help as a fallback option should we struggle to get things up and running.

## Instructions

1. Create a static page that illustrates invoicing functionality. Try and make it match the following design as closely as possible. Feel free to use any of the assets in the `assets` directory to achieve this.
![Hiring Process](assets/screen1.jpg?raw=true)

2. You'll note in the above image there are navigation tabs - these should reflect the part of your application you are on currently. If you're building for mobile you will likely want to think about building these using the usual design language people would expect - which may mean they do not appear at the top as they do in the image above(!)

3. The second tab should route through to a savings calculator:
![Hiring Process](assets/screen2.jpg?raw=true)
This should show you how much you save when you switch to Ember. Ember's pricing is £39 per month + £4 per employee.

4. The code for the calculation should sit behind an API - it's up to you how you want to set up this API locally. We use [NextJS](https://nextjs.org/docs/api-routes/introduction) internally.

5. **Stretch goal:** If you have time consider adding a form to your app which allows users to apply for an account with us - so they can enter their details and save those details to a back end service/DB. It's up to you how you want to set up this API and store the data locally. We use [Prisma](https://www.prisma.io/docs/getting-started/quickstart-typescript), [GraphQL](https://www.prisma.io/docs/concepts/overview/prisma-in-your-stack/graphql) and [PostgreSQL](https://www.prisma.io/docs/concepts/database-connectors/postgresql) internally.

6. **Stretch goal:** Add tests and test coverage if you still have time remaining.

