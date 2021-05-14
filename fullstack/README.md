# Full Stack Engineer - Coding Exercise

_**TIMEBOX:**_    1-2 hours - max!

_**ENVIRONMENT:**_ node + yarn (or npm)

_**LANGUAGES:**_
- TypeScript (or JavaScript)

_**FRAMEWORKS:**_
- [Expo (optional but preferred)](https://expo.io/)
- [React Native](https://reactnative.dev/) (or [React](https://reactjs.org/docs/getting-started.html))
- [Next.js](https://nextjs.org/) (or [Express](https://expressjs.com/))
- [Prisma](https://www.prisma.io/docs/getting-started/quickstart-typescript) (optional)
- [React Native Testing Library](https://testing-library.com/docs/react-native-testing-library/intro/) / [Jest](https://jestjs.io/) (BOTH optional)

_**TECHNOLOGY:**_ Web and/or Mobile

_**TESTS:**_ optional

_**DOCS:**_ mandatory

# Overview

This coding exercise is to implement the best possible solution to one of the following exercises in the time allotted. We're evaluating your ability to take a set of requirements and spike a solution that demonstrates craftsmanship and attention to detail. This is **NOT** a test of how well you know the features of React Native/React! Please do not try to impress us with overly complex and obtuse solutions. If you want to impress us, build something that is beautiful, intuitive and easy to maintain, debug, test and extend! 🙂

Ideally your solution will have some way to run locally and visualise the results so we can fully analyse the experience (and not just the source code).

Feel free to include some screenshots in your repo as this may help as a fallback option should we struggle to get things up and running.

# Exercises (choose ONE of the following)

## Exercise 1: Visualising Compensation and Benefits

1. Create a static page that illustrates invoicing functionality. Try and make it match the following design as closely as possible. Feel free to use any of the assets in the `assets` directory to achieve this.
![Hiring Process](assets/exercise1/screen1.jpg?raw=true)

2. You'll note in the above image there are navigation tabs - these should reflect the part of your application you are on currently. If you're building for mobile you will likely want to think about building these using the usual design language people would expect - which may mean they do not appear at the top as they do in the image above(!)

3. The second tab should route through to a savings calculator:
![Hiring Process](assets/exercise1/screen2.jpg?raw=true)
This should show you how much you save when you switch to Ember. Ember's pricing is £39 per month + £4 per employee.

4. The code for the calculation should sit behind an API - it's up to you how you want to set up this API locally. We use [NextJS](https://nextjs.org/docs/api-routes/introduction) internally.

5. **Stretch goal:** If you have time consider adding a form to your app which allows users to apply for an account with us - so they can enter their details and save those details to a back end service/DB. It's up to you how you want to set up this API and store the data locally. We use [Prisma](https://www.prisma.io/docs/getting-started/quickstart-typescript), [GraphQL](https://www.prisma.io/docs/concepts/overview/prisma-in-your-stack/graphql) and [PostgreSQL](https://www.prisma.io/docs/concepts/database-connectors/postgresql) internally.

6. **Stretch goal:** Add tests and test coverage if you still have time remaining.

## Exercise 2: Visualising Compensation and Benefits

1. Create a simple form to upload a CSV/JSON file with compensation data of an organisation.

2. Your API should **NOT** include the ability for file storage/IO but should be backed by a DB where this data is stored once uploaded. It's up to you how you want to set up this API and store the data locally. We use [Prisma](https://www.prisma.io/docs/getting-started/quickstart-typescript), [GraphQL](https://www.prisma.io/docs/concepts/overview/prisma-in-your-stack/graphql) and [PostgreSQL](https://www.prisma.io/docs/concepts/database-connectors/postgresql) internally.

3. Use the sample files in [assets/exercise2](assets/exercise2) (which were sourced from a [publically available data set](https://sourceful.us/doc/572/ask-a-manager-salary-survey-2019-responses). Alternatively, if your feeling ambitious, create your own simple data set using e.g. [faker](https://www.npmjs.com/package/faker).

4. Create an API endpoint which can read and serve data requested from your local DB. It's up to you how you want to set up this API locally. We use [NextJS](https://nextjs.org/docs/api-routes/introduction) internally.

5. Create a simple tabular view (served by the API you created in step 4).

6. **Stretch goal:** Add the ability to be able to sort or search by any unique identifiers (name, email, etc) so I can find specific rows.

6. **Stretch goal:** Add tests and test coverage if you still have time remaining.

