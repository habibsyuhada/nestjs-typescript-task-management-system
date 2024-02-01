
# nestjs-typescript-task-management-system
This project uses Nest.js and typescript to implement project and task with their respective CRUD endpoints. This endpoints are protected, so, to consume them, you need to register yourself to get a valid JWT. 

The endpoints of the resources are:
- [ ] /projects
- [ ] /users
  
To register or to login:
- [ ] /auth/register
- [ ] /auth/login

The documentation (swagger) can be found at:
- [ ] /docs

## Table of Contents
- [Prerequisites](#prerequisites)
- [Environment Variables](#environment-variables)
- [Installation](#installation)
- [Running Tests](#running-tests)

## Prerequisites
- [nodejs versión 18](https://nodejs.org/en/)

## Environment Variables
To run this project, you will need to add the following environment variables to your .env file
`DBTYPE`
`DBHOST`
`DBNAME`
`DBUSER`
`DBPASSWORD`
`DBPORT`
`PREFIXTABLE`
`JWTSECRET`
`PORT`

## Installation
Clone the project
```bash
git clone https://github.com/habibsyuhada/nestjs-typescript-task-management-system
```
Go to the project directory
```bash
cd nestjs-typescript-task-management-system
npm install
```
To start the server
```bash
npm run start
```

## Running Tests
To run tests, run the following command
```bash
npm run test // Unit Tests
npm run test:e2e // Integration Tests
```