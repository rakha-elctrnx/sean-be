# Express Js API

## Features

- **NoSQL database**: MongoDB object data modeling using Mongoose
- **Authentication and authorization**: using passport
- **Validation**: request data validation using Joi
- **Logging**: using winston and morgan
- **Testing**: unit and integration tests using Jest
- **Error handling**: centralized error handling mechanism
- **API documentation**: with swagger-jsdoc and swagger-ui-express
- **Process management**: advanced production process management using PM2
- **Dependency management**: with Yarn
- **Environment variables**: using dotenv and cross-env
- **Security**: set security HTTP headers using helmet
- **Sanitizing**: sanitize request data against xss and query injection
- **CORS**: Cross-Origin Resource-Sharing enabled using cors
- **Compression**: gzip compression with compression
- **CI**: continuous integration with Travis CI
- **Docker support**
- **Code coverage**: using coveralls
- **Code quality**: with Codacy
- **Git hooks**: with husky and lint-staged
- **Linting**: with ESLint and Prettier
- **Editor config**: consistent editor configuration using EditorConfig

## Commands

Running locally:

```bash
yarn dev
```

Running in production:

```bash
yarn start
```

Testing:

```bash
# run all tests
yarn test

# run all tests in watch mode
yarn test:watch

# run test coverage
yarn coverage
```

Docker:

```bash
# run docker container in development mode
yarn docker:dev

# run docker container in production mode
yarn docker:prod

# run all tests in a docker container
yarn docker:test
```

Linting:

```bash
# run ESLint
yarn lint

# fix ESLint errors
yarn lint:fix

# run prettier
yarn prettier

# fix prettier errors
yarn prettier:fix
```

## API Documentation

To view the list of available APIs and their specifications, run the server and go to `http://localhost:3000/v1/docs` in your browser. This documentation page is automatically generated using the [swagger](https://swagger.io/) definitions written as comments in the route files.