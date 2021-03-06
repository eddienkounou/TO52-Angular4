# Dedal [![MIT license](http://img.shields.io/badge/license-MIT-lightgrey.svg)](http://opensource.org/licenses/MIT)


The frontend is generated with [Angular CLI](https://github.com/angular/angular-cli). The backend is based on [Angular-Full-Stack](https://github.com/DavideViolante/Angular-Full-Stack). Whole stack in [TypeScript](https://www.typescriptlang.org).

This project uses the [MEAN stack](https://en.wikipedia.org/wiki/MEAN_(software_bundle)):
* [**M**ongoose.js](http://www.mongoosejs.com) ([MongoDB](https://www.mongodb.com)): database
* [**E**xpress.js](http://expressjs.com): backend framework
* [**A**ngular 4](https://angular.io): frontend framework
* [**N**ode.js](https://nodejs.org): runtime environment

Other tools and technologies used:
* [Angular CLI](https://cli.angular.io): frontend scaffolding
* [Bootstrap](http://www.getbootstrap.com):basic layout
* [material-kit](http://demos.creative-tim.com/material-kit/index.html): advanced layout and styles
* [Font Awesome](http://fontawesome.io): icons
* [Material icons](https://material.io/icons/): more icons
* [JSON Web Token](https://jwt.io): user authentication
* [Angular 2 JWT](https://github.com/auth0/angular2-jwt): JWT helper for Angular
* [Bcrypt.js](https://github.com/dcodeIO/bcrypt.js): password encryption

## Prerequisites
1. Install [Node.js](https://nodejs.org) and [MongoDB](https://www.mongodb.com)
2. Install Angular CLI: `npm i -g @angular/cli`
3. From project root folder install all the dependencies: `npm i`

## Run
### Development mode
`npm run dev`: [concurrently](https://github.com/kimmobrunfeldt/concurrently) execute MongoDB, Angular build, TypeScript compiler and Express server.

A window will automatically open at [localhost:4200](http://localhost:4200) on your default browser. Angular and Express files are being watched. Any saved change automatically creates a new bundle, restart Express server and reload your browser.

### Production mode
`npm run prod`: run the project with a production bundle and AOT compilation listening at [localhost:3000](http://localhost:3000)

## Preview
![Preview](https://github.com/alitriki/TO52_Angular4/blob/dev/demo.gif "Preview")

## Please open an issue if
* you have any suggestion to improve this project
* you noticed any problem or error
* you have a question

## To do
* More functionalities

## Running unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests
Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `npm start`.

## Running TSLint
Run `ng lint` (frontend) and `npm run lintbe` (backend) to execute the linter via [TSLint](https://palantir.github.io/tslint/).

## Further help
To get more help on the `angular-cli` use `ng --help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Joined documents
We joined to this repository the progress [report](https://github.com/alitriki/TO52_Angular4/blob/master/Rapport.pdf) and the presentation support in [pdf](https://github.com/alitriki/TO52_Angular4/blob/master/presentation.pdf) and [pptx](https://github.com/alitriki/TO52_Angular4/blob/master/presentation.pptx).

### Authors
* [Ali Triki](https://github.com/alitriki)
* [Eddie Nkounou](https://github.com/eddienkounou)
