# LAB - 07

## HTTP and REST

### Author: Alex Spencer

### Links and Resources
* [submission PR](https://github.com/alexspencer-401-advanced-javascript/simple-api/pull/1)
* [travis](https://travis-ci.com/alexspencer-401-advanced-javascript/lab-07)

#### Documentation
* openapi.json documentation can be found in `/docs/openapi.json`

#### Running the app

**Describe what npm scripts do**
* Scripts: 
  - "start": "json-server --watch data/db.json --routes routes.json --id _id",
  - "lint": "eslint **/*.js",
  - "test": "jest --verbose --coverage",
  - "test-watch": "jest --watchAll --verbose --coverage",
  - "jsdoc": "jsdoc -c ./docs/config/jsdoc.config.json"