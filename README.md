# A List of Foundational JavaScript  Tools

_By Kalina Wu, Sarah Fischer, and Ivan Storck_

In our boot camps, students are introduced to several tools and libraries to expand the abilities of their code. Kalina, one of our current JavaScript students, compiled a list of these tools and wanted to share it with other Code Fellows.

[Ivan Storck](https://twitter.com/ivanoats), our [JavaScript Boot Camp](https://www.codefellows.org/javascript-bootcamp) instructor, used [Kalina's](https://www.linkedin.com/in/kalinawu) list to draft up this helpful mind map:

![JavaScript Tools Mind Map](JavaScriptTools.png)

## Update

This article and associated [MindNode](https://mindnode.com/) mind map (OPML) are
now on Github so that Pull Requests can be made to it. Send us your suggestions
to add new and popular tools.

## General

**Scaffolding Tools** (for starting projects)

* [Yeoman](http://yeoman.io/) - Yeoman is a robust and opinionated client-side stack, comprising tools and frameworks that can help developers quickly build beautiful web applications.

**Build Tools** (automation)

* [Grunt.js](http://gruntjs.com/) - The Grunt ecosystem is huge and it's growing every day. With literally hundreds of plugins to choose from, you can use Grunt to automate just about anything with a minimum of effort.
	* [Pint.js](http://www.pintjs.com/) (Grunt helper) - Pint is a small, asynchronous, dependency-aware wrapper around Grunt, attempting to solve some of the problems that accompany a build process at scale.
* [Gulp.js](http://gulpjs.com/) - Gulp's use of streams and code-over-configuration makes for a simpler and more intuitive build.
* [Browserify.js](http://browserify.org/) (for browser) - Browserify is a development tool that allows us to write node.js-style modules that compile for use in the browser. Just like node, we write our modules in separate files, exporting external methods and properties using the module.exports and exports variables.
* [Uglify.js](http://marijnhaverbeke.nl//uglifyjs) - Uglify.js is a JavaScript parser / mangler / compressor / beautifier library for NodeJS.

**Package Management Tools**

* [Homebrew](http://brew.sh/) (Mac OS) - Homebrew installs the stuff you need that Apple didn't.
* [Apt](https://help.ubuntu.com/12.04/serverguide/apt-get.html) (Ubuntu) - The apt-get command is a powerful command-line tool, which works with Ubuntu's Advanced Packaging Tool (APT) performing such functions as installation of new software packages, upgrade of existing software packages, updating of the package list index, and even upgrading the entire Ubuntu system.
* [NPM](https://www.npmjs.org/) - npm is the official package manager for Node.js.
* [Bower](http://bower.io/) - Bower is a package manager for the web.

## Front End

**MVC Frameworks**

* [Backbone.js](http://backbonejs.org/) - Backbone.js gives structure to web applications by providing models with key-value binding and custom events, collections with a rich API of enumerable functions, and views with declarative event handling. It connects it all to your existing API over a RESTful JSON interface.
* [Ember.js](http://emberjs.com/) - Ember makes Handlebars templates even better by ensuring your HTML stays up-to-date when the underlying model changes. To get started, you don't even need to write any JavaScript.
* [Angular.js](http://angularjs.org/) - AngularJS lets you extend HTML vocabulary for your application. The resulting environment is extraordinarily expressive, readable, and quick to develop.

**Templates**

* [Handlebars.js](http://handlebarsjs.com/) - Handlebars provides the power necessary to let you build semantic templates effectively with no frustration. Mustache templates are compatible with Handlebars, so you can take a Mustache template, import it into Handlebars, and start taking advantage of the extra Handlebars features.
* [Mustache.js](http://mustache.github.io/) (less built-out than Handlebars) - Mustache is a simple web template system with implementations available for ActionScript, C++, Clojure, CoffeeScript, ColdFusion, D, Erlang, Fantom, Go, Java, JavaScript, Lua, .NET, Objective-C, Pharo, Perl, PHP, Python, Ruby, Scala and XQuery.
* [Jade](http://jade-lang.com/) - Jade is a node template engine designed primarily for server-side templating in node.js.
* [Haml-js](https://github.com/creationix/haml-js) - Haml-js allows the [Haml](http://haml.info/) syntax to be used in a JavaScript project. It has most of the same functionality as the original Haml.
* [Eco](https://github.com/sstephenson/eco) - Eco lets you embed [CoffeeScript](http://coffeescript.org/) logic in your markup.
* [Dust](http://akdubya.github.io/dustjs) - A logic-less templating engine used in LinkedIn. LinkedIn even has its own fork of the project which can be found [here](https://github.com/linkedin/dustjs)

**Testing**

* [Casper.js](http://casperjs.org/) - CasperJS is a navigation scripting and testing utility for [PhantomJS](http://phantomjs.org/) and SlimerJS written in Javascript.
* [Zombie.js](http://zombie.labnotes.org/) - Zombie.js is a lightweight framework for testing client-side JavaScript code in a simulated environment. No browser required.


## Back End

**Servers**

* [Express](http://expressjs.com/) - Express is a web application framework for Node.
* [Node](http://nodejs.org/) - Node.js is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications.

**Databases**

* [MongoDB](https://www.mongodb.org/) - MongoDB is an open-source document database, and the leading NoSQL database.
* [Postgresql](http://www.postgresql.org/) - PostgreSQL is a powerful, open source, object-relational database system.
* [SQL](http://www.sqlcourse.com/intro.html) - SQL is used to communicate with a database. According to the American National Standards Institute, it is the standard language for relational database management systems.

**Architectural Style**

* RESTful - Representational State Transfer is an architectural style consisting of a coordinated set of architectural constraints applied to components, connectors, and data elements, within a distributed hypermedia system.

**Testing**

* [Cucumber.js](https://github.com/cucumber/cucumber-js) - Cucumber.js takes the popular [behavior-driven development tool](http://cukes.info/) and applies it to your JavaScript stack.
* [Jasmine](http://jasmine.github.io/) - Jasmine is a behavior-driven development testing framework for JavaScript. It does not rely on browsers, DOM, or any JavaScript framework. Thus it's suited for websites, Node.js projects, or anywhere that JavaScript can run.
* [Mocha](http://visionmedia.github.io/mocha/) - Mocha is a feature-rich JavaScript test framework running on node.js and the browser, making asynchronous testing simple and fun.
* [Q-Unit](https://qunitjs.com/) - Q-Unit is a powerful, easy-to-use JavaScript unit testing framework. It's used by the jQuery, jQuery UI and jQuery Mobile projects and is capable of testing any generic JavaScript code.

**Assertion Libraries**

* [Chai](http://chaijs.com/) - Chai is a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.

**Functional Programming Tools**

* [Underscore.js](http://underscorejs.org/) - Underscore is a JavaScript library that provides a whole mess of useful functional programming helpers without extending any built-in objects.
* [Lo-Dash](http://lodash.com/) - Lo-Dash is a utility library delivering consistency, customization, and performance.
