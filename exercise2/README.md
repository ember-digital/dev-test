# Exercise 2: Upload, store and display data

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

1. Create a simple form to upload a CSV/JSON file with compensation data of an organisation.

2. Your API should be backed by a DB where this data is stored once uploaded. It's up to you how you want to set up this API and store the data locally. We use [Prisma](https://www.prisma.io/docs/getting-started/quickstart-typescript), [GraphQL](https://www.prisma.io/docs/concepts/overview/prisma-in-your-stack/graphql) and [PostgreSQL](https://www.prisma.io/docs/concepts/database-connectors/postgresql) internally.

3. Use the sample files in [assets](assets) (which were sourced from a [publically available data set](https://sourceful.us/doc/572/ask-a-manager-salary-survey-2019-responses)). Alternatively, if you're feeling ambitious, create your own simple data set using e.g. [faker](https://www.npmjs.com/package/faker).

4. Create an API endpoint which can read and serve data requested from your local DB. It's up to you how you want to set up this API locally. We use [NextJS](https://nextjs.org/docs/api-routes/introduction) internally.

5. Create a simple tabular view (served by the API you created in step 4).

6. **Stretch goal:** Add the ability to be able to sort or search by any unique identifiers (name, email, etc) so I can find specific rows.

6. **Stretch goal:** Add tests and test coverage if you still have time remaining.

