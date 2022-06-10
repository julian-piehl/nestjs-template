<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications using <a href="https://nestjs.com" target="_blank">NestJS</a>.</p>
</p>

## Description

Ready for you. Dont worry about setting up:

- Docker
- Devcontainer
- Swagger
- And other default Settings for NestJS

## Installation

```bash
$ npm install
```

## Running the app (Docker)

```bash
# development
$ npm run docker:dev:up

# production mode
$ npm run docker:up
```

## Stopping the app (Docker)

```bash
# development
$ npm run docker:dev:down

# production mode
$ npm run docker:down
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Swagger

When you start the application in development mode Swagger gets available at http://localhost:3000/api
