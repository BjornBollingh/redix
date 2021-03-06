# Simple React example using Redix containers to easily enable dependency injection

This example shows how to create presentational components and container components using the Redix container (and without Redux).

Check this file src/containers/PhotoListContainer.js to see how to enable dependency injection in your containers for an easier unit testing.

Check this file test/unit/containers/PhotoListContainer.spec.js to see how to unit test a container that doesn't use `react-redux`. Tests use Facebook TestUtils, AirBnB Enzyme and Redix DI

## Usage

```
npm install
npm start
open http://localhost:3000
```

## Unit testing

This example project includes unit tests. There are examples using Facebook TestUtils, AirBnB Enzyme and Redix DI

```
npm test
```

## Resources

* [Post (React Dependency Injection, write unit tests easily with Redix)](http://alexlobera.com/react-dependency-injection-write-unit-tests-easily-with-redix/)
* [Redix on Github](https://github.com/alexlbr/redix)
* Ping @alex_lobera on Twitter
