![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## 00Deployment
### Author: Jared
### Links and Resources
[![Build Status](https://www.travis-ci.com/jaredpattison/00-deployment.svg?branch=master)](https://www.travis-ci.com/jaredpattison/00-deployment)
* [repo](https://github.com/jaredpattison/00-deployment)
* [travis](https://www.travis-ci.com/jaredpattison/00-deployment)
* [server](https://jared00.herokuapp.com/)

### Modules
#### `pol.js`
##### Exported Values and Methods
* `isAlive`
* Returns true or false
  * false if a parameter is sent

###### `foo(thing) -> string`
Usage Notes or examples

###### `bar(array) -> array`
Usage Notes or examples

### Setup
#### `.env` requirements
* `PORT` - Defined in the ENV
* `MONGODB_URI` - URL to the running mongo instance/db

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns `true`

#### Tests
* npm tests (Runs Unit Tests)
* npm run lint (Runs Linter Tests)

#### UML
Link to an image of the UML for your application and response to events
