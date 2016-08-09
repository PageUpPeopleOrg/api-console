# RAML Console

This repo is a clone of [Mulesoft's RAML Console](https://github.com/mulesoft/api-console)

[![Build Status](https://travis-ci.org/PageUpPeopleOrg/api-console.svg)](https://travis-ci.org/PageUpPeopleOrg/api-console) 

An API console for [RAML](http://raml.org) (Restful Api Modeling Language) documents. The RAML Console allows browsing of API documentation and in-browser testing of API methods.

## Development

### Prerequisites

To run the console, you'll need the following:

* [Node JS](http://nodejs.org/)
* [NPM](https://npmjs.org/)
* [Ruby](https://www.ruby-lang.org)

### First Time Setup

1. Install Sass - `gem install sass`
1. Install grunt-cli globally - `npm install -g grunt-cli`
1. Install bower globally - `npm install -g bower`
1. Install the console's NPM packages - `npm install`
1. Install the console's Bower packages - `bower install`

### Running the server

    $ grunt
    $ open http://localhost:9000

## Testing

### Prerequisites

To run tests, you'll need the following:

* [Node JS](http://nodejs.org/)
* [NPM](https://npmjs.org/)
* [Protractor](http://angular.github.io/protractor)
* [Ruby](https://www.ruby-lang.org)

### First Time Setup

1. Install Sass - `gem install sass`
1. Install grunt-cli globally - `npm install -g grunt-cli`
1. Install protractor globally - `npm install -g protractor`
1. Install the console's NPM packages - `npm install`
1. Run  `node_modules/grunt-protractor-runner/node_modules/protractor/bin/webdriver-manager update`

### Running Tests

    $ grunt regression
    
