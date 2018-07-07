# README Living Style Guide
- What the project is about? (short project description)
- Why does this project exist? (short motivation)
- What makes your project stand out? (features)

## Getting Started
- Instructions to get copy of the project
- Instructions to run project on local machine (for development and testing)

### Prerequisites
- What is needed to install the software?
- How to install it?
```
Give examples
```
# Code Example
- Show what the library does.
- How does your project solve developers problem (see: code example).
- Show an obvious API
- Make code short and concise.

### Installation
- How to get development environment running?
- step-by-step series of examples (descriptions, how to install, step by step)
Step 1

```
Give the example
```
Repeat

```
until finished
```
End with Example of 
- getting some data out of the system 
- using data for a little demo

## Screenshots
Include logo/demo screenshot.


## Build status
- What is the build status of continuos integration?

##  Code style
Living Style Guide uses the [StandardJS](https://standardjs.com) style and [Common Mark](http://commonmark.org) for markdown.

## Testing

#### [Mocha](https://mochajs.org)
Mocha is a feature-rich JavaScript test framework running on Node.js and in the browser, making asynchronous testing simple and fun. Mocha tests run serially, allowing for flexible and accurate reporting, while mapping uncaught exceptions to the correct test cases. Hosted on GitHub.

To run Mocha’s tests, you will need GNU Make or compatible; Cygwin should work.

````
$ cd /path/to/mocha
$ npm install
$ npm test
To use a different reporter:

$ REPORTER=nyan npm test
````

##### Getting starting

````
$ npm install mocha
$ mkdir test
$ $EDITOR test/test.js # or open with your favorite editor
````

In your editor:

````
var assert = require('assert');
describe('Array', function() {
  describe('#indexOf()', function() {
    it('should return -1 when the value is not present', function() {
      assert.equal([1,2,3].indexOf(4), -1);
    });
  });
});
````

Back in the terminal:

````
$ ./node_modules/mocha/bin/mocha

  Array
    #indexOf()
      ✓ should return -1 when the value is not present


  1 passing (9ms)
  
````

Set up a test script in package.json:

````
"scripts": {
    "test": "mocha"
  }
````

Run tests with:

````
$ npm test
````

#### [Chai JS](http://www.chaijs.com)
Chai is a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.
Chai is available for both node.js and the browser using any test framework you like. There are also a number of other tools that include Chai.

Node.js
Package is available through npm:

````
npm install chai
````

Recommend adding it to package.json devDependencies using a * as the version tag. This will ensure that you always have the most recent version after running npm install, which can be especially powerful when paired with a continuous integration tool.

````
"devDependencies": {
  "chai": "*",
  "mocha": "*"
}, "//": "mocha is our preference, but you can use any test runner you like"
````

Browser
Include the chai browser build in your testing suite.

````
<script src="chai.js" type="text/javascript"></script>
````

This will provide chai as a global object, or define it if you are using AMD.

The latest tagged version will be available for hot-linking at http://chaijs.com/chai.js. If you prefer to host yourself, use the chai.js file from the root of the github project. We recommend that you always use a version tag as your starting point, so the tag download list is the best place to start.

Currently supports all modern browsers: IE 9+, Chrome 7+, FireFox 4+, Safari 5+. Please note that the should style is currently not compatible with IE9.

If you want to know if your browser is compatible, run the online test suite.

### End-to-end-tests
- Explain what these tests test and why
```
Give an example
```
### Coding style tests
- Explain what these tests test and why
```
Give an example
```
## Deployment
Add additional notes about how to deploy this on a live system

How to use?
If people like your project they’ll want to learn how they can use it. To do so include step by step guide to use your project.

## Code Dependencies 
[Living Style Guide](http://www.livingstyleguide.org) is built with the dependencies listed below.


#### [JSDOM](https://github.com/jsdom/jsdom)
jsdom is a pure-JavaScript implementation of many web standards, notably the WHATWG DOM and HTML Standards, for use with Node.js. In general, the goal of the project is to emulate enough of a subset of a web browser to be useful for testing and scraping real-world web applications. The latest versions of jsdom require Node.js v6 or newer. (Versions of jsdom below v10 still work with Node.js v4, but are unsupported.) As of v10, jsdom has a new API (documented below). The old API is still supported for now; see its documentation for details.


#### [MARKDOWN IT](https://github.com/markdown-it/markdown-it)
Markdown parser done right. Fast and easy to extend.


#### [MDURL](https://github.com/markdown-it/mdurl)
URL utilities for markdown-it parser.


#### [LINKIFY](https://github.com/SoapBox/linkifyjs)
Linkify is a small yet comprehensive JavaScript plugin for finding URLs in plain-text and converting them to HTML links. It works with all valid URLs and email addresses.


#### [ENTITIES](https://github.com/fb55/entities)
En- & decoder for XML/HTML entities.


#### [ARGPARSE](https://github.com/nodeca/argparse)
CLI arguments parser for node.js. Javascript port of python's argparse module (original version 3.2). That's a full port, except some very rare options, recorded in issue tracker.


#### [ESLINT](https://github.com/eslint/eslint)
ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code. In many ways, it is similar to JSLint and JSHint with a few exceptions:

* ESLint uses Espree for JavaScript parsing.
* ESLint uses an AST to evaluate patterns in code.
* ESLint is completely pluggable, every single rule is a plugin and you can add more at runtime.



## Contributing
Please read [CONTRIBUTING.md]() for details on our code of conduct, and the process for submitting pull requests to us.

## Authors
- Copyright 2018++ -[Nico Hagenburger](https://www.hagenburger.net).
- Get in touch with [@hagenburger](https://twitter.com/hagenburger) on Twitter or [open an issue](https://github.com/hagenburger/pimd/issues/new).

## Contributors
- [contributors](https://github.com/your/project/contributors) who participated in this project.

## License
This project is licensed under the MIT License. See [MIT-LICENSE](LICENSE.md) for details.

## Acknowledgments
Copyright 2018++ [Nico Hagenburger](https://github.com/hagenburger/). See MIT-LICENSE for details. Get in touch with @hagenburger on Twitter or open an issue.

* [ArtNerdNet](http://www.github.com/artnerdnet)
* [Diana Vilé](http://www.github.com/dianaviale)
