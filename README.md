# deploy-wrkshp

## codefellows 401 JS prework deployment workshop

### Author: Kevin Dreyer

### Links and Resources
* [submission PR](https://github.com/kevindreyer-CF401JSd/deploy-wrkshp/pull/1)
* [travis](https://travis-ci.com/kevindreyer-CF401JSd/deploy-wrkshp)
* [front-end](https://kevindreyer-labdplywrkshp.herokuapp.com/)

#### Documentation
* [jsdoc](https://kevindreyer-labdplywrkshp.herokuapp.com/docs)

### Modules
#### `pol.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
The isAlive() method returns a boolean based on the arg sent in.

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns true or false
* Endpoint: `/docs`
  * Renders Developer Documentation
  
#### Tests
* Unit Tests: `npm run test`
* Lint Tests: `npm run lint`
* Assertions Made
  * Assert that isAlive() properly returns a boolean
* Assertions Remaining
  * ... Things I want to tests, but didn't yet.

#### UML

![UML Diagram](whiteboard.jpg)
