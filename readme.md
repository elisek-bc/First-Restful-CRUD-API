# First CRUD API

## What?
This is an execution of a tutorial found [here](https://www.callicoder.com/node-js-express-mongodb-restful-crud-api-tutorial/) on making a Restful CRUD API with Node.js, Express and MongoDB.

## Contributors
I, Elise, am the only contributor to this project.

## Timing
This exercise was done as an introduction to NodeJS and making your own API's. There's not really a deadline on it. It's part of my educational training at Becode. I worked on it on the 11th June 2019.

## How?
* MongoDB
* Express
* NodeJS
* Javascript

## Answers on external questions relating to NodeJS

Trying to get a better understanding of the following subjects:

### What is NodeJS?
> In simple terms, it’s a JavaScript *free and open source cross-platform* for server-side programming that allows users to build *network applications* quickly.
In general, Node is a great tool to quickly get an *api* up and running.

> Run it: The first thing you do when you get any kind of Node project is that you navigate to the directory that it’s in and in terminal write: *npm install*
### What is NPM?
> It is the official package manager for Node and is bundled & installed automatically with the environment. Npm makes it easy for JavaScript developers to share the code that they have created to solve particular problems and for other developers to reuse that code in their own application. npm consists of three distinct components:

* the website
* the Command Line Interface (CLI) aka npm client
* the registry(database of information about packages that people are sharing)

*sidenote: packages are building blocks of code*
### What are some of the most popular npm packages
**npm packages are ways to reuse the code from developers and also share your code with them.**

1. express - Fast, unopinionated, minimalist web framework for node.
2. body-parser - Node.js body parsing middleware.
3. lodash - Lodash makes JavaScript easier by taking the hassle out of working with arrays, numbers, objects, strings, etc.
4. babel-core - most popular JavaScript transpiler.
5. async - utility module which provides straight-forward, powerful functions for working with asynchronous JavaScript.
>The best way to manage locally installed npm packages is to create a *package.json* file. At its simplest, a package.json file can be described as a manifest of your project that includes the packages and applications it depends on, information about its unique source control, and specific metadata like the project's name, description, and author. It serves as documentation for what packages your project depends on. It allows you to specify the versions of a package that your project can use using semantic versioning rules. Makes your build reproducible which means that its way easier to share with other developers.

>Run it: The npm init command is a step-by-step tool to scaffold out your project. It will prompt you for input for a few aspects of the project in the following order.
### What are some of the most popular frameworks to use with NodeJS? What are the advantages / disadvantages (https://2018.stateofjs.com/back-end-frameworks/overview/)
#### ExpressJS
ExpressJS is a web framework that let’s you structure a web application to handle multiple different http requests at a specific url.

Express is a *minimal, open source and flexible* Node.js web app framework designed to make developing websites, web apps, & API’s much easier.

* Easy learning curve
* Rich package eco system
* Good documentation
* Simple & lightweight

##### **BUT**

* Clumsy programming style
* Slightly diminisching momentum or popularity

#### Next JS

* Elegant programming style & patterns
* Fast performance
* Easy learning curve
* Good documentation

##### **BUT**

* Bloated and complex
* Clumsy programming style

#### KOA

* Elegant programming style & patterns
* Simple & lightweight
* Fast performance

##### **BUT**

* Diminishing popularity
* Clumsy programming style
* Small package ecosystem

#### Meteor

* Full featured and powerful
* Good documentation
* Easy learning curve
* Elegant programming style & patterns

##### **BUT**

* Diminishing popularity
* Bloated and complex

### What databases can you use with those frameworks?
### What's the difference between a database like MySQL and an orm like MongoDB.
> MySQL is a popular open-source relational database management system (RDBMS) that is developed, distributed and supported by Oracle Corporation. Like other relational systems, MySQL stores data in tables and uses structured query language (SQL) for database access. In MySQL, you pre-define your database schema based on your requirements and set up rules to govern the relationships between fields in your tables. *Any changes in schema necessitates a migration procedure that can take the database offline or significantly reduce application performance.*

> MongoDB is a non-relational database developed by MongoDB, Inc. MongoDB stores data as documents in a binary representation called BSON (Binary JSON). Related information is stored together for fast query access through the MongoDB query language. Fields can vary from document to document; there is no need to declare the structure of documents to the system – documents are self-describing. *If a new field needs to be added to a document, then the field can be created without affecting all other documents in the collection, without updating a central system catalog, and without taking the system offline. Optionally, schema validation can be used to enforce data governance controls over each collection.*




## Struggles
Getting things done in Postman seems difficult at first. Once you get the right settings it works out eventually.