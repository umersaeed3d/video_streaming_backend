<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Description

A NestJS backend for video streaming app.

## Endpoints

- Login : /api/v1/user/signin - Method : {POST} - Payload : {email, password}
- Sign up : /api/v1/user/signup - Method : {POST} - Payload : {fullname, email, password}
- Add Video : /api/v1/video - Method : {POST} - Payload : {title, video, cover}
- Get All Videos : /api/v1/video - Method : {GET} - Payload : {}
- Get Specific Video : /api/v1/video?id=${videoId} - Method : {GET} - Payload {}

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
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


