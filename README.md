**Check out our latest demo:** https://github.com/strongloop/strong-gateway-demo

#loopback-demo

This is a [LoopBack][loopback] example and tutorial list maintained by [StrongLoop][strongloop].

- [Overview](#overview)
- [Tutorials](#tutorials)
  - [Getting started](#getting-started)
  - [Topic-specific](#topic-specific-examples)
  - [FAQ](#faq-tutorials)
  - [Deprecated](#deprecated-tutorials)
- [Examples](#examples)
  - [Community](#community-examples)
- [Deprecated](#deprecated-examples)
- [Terminology](#terminology)

##Overview

This README provides a complete reference for all demo apps for LoopBack. Make sure you:

- Familiarize yourself with the [terminology](#terminology) we use in all demos
- Complete each ["Getting started" tutorial](#getting-started) in the listed order
- Try out any other demo in any order

###Before starting any demo

Make sure:

-  The demo is not [deprecated](deprecated-demos)
-  The demo is listed in this README (otherwise we do not officially maintain it)

##Tutorials

###Getting started

>You only have to complete **ONE** tutorial number 2 before moving onto tutorial
number 3

|Order|Name|Description|
|---|---|---|
|1|[loopback-getting-started](https://github.com/strongloop/loopback-getting-started)|The basics of LoopBack.  Follow along in [Getting started with LoopBack](http://docs.strongloop.com/display/LB/Getting+started+with+LoopBack) to build the example.|
|2|[loopback-getting-started-intermediate](https://github.com/strongloop/loopback-getting-started-intermediate)| Full-stack example that builds on `loopback-getting-started` to demonstrate intermediate level features of LoopBack.  Follow instructions in [Getting started part II](http://docs.strongloop.com/display/LB/Getting+started+part+II) to build the example.|
|3|[loopback-example-mongodb](https://github.com/strongloop/loopback-example-mongodb)|LoopBack with MongoDB.|
|3|[loopback-example-mssql](https://github.com/strongloop/loopback-example-mssql)|LoopBack with Microsoft SQL Server.|
|3|[loopback-example-mysql](https://github.com/strongloop/loopback-example-mysql)|LoopBack with MySQL.|
|3|[loopback-example-oracle](https://github.com/strongloop/loopback-example-oracle)|LoopBack with Oracle.|
|3|[loopback-example-postgresql](https://github.com/strongloop/loopback-example-postgresql)|LoopBack with PostgreSQL.|
|4|[loopback-example-relations](https://github.com/strongloop/loopback-example-relations)|Model relations and filtering via REST|
|5|[loopback-example-app-logic](https://github.com/strongloop/loopback-example-app-logic)|How to add your own logic to a LoopBack app|
|6|[loopback-example-access-control](https://github.com/strongloop/loopback-example-access-control)|Controlling access to your API endpoints|

###Topic-specific examples

You can follow these examples in any order since they are self-contained and
specific to a particular topic.

|Name&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Description  |
|---|---|
|[loopback-android-getting-started](https://github.com/strongloop/loopback-android-getting-started)            |How to use the LoopBack Android SDK |
|[loopback-component-push](https://github.com/strongloop/loopback-component-push)  |LoopBack 2.x examples are in the `examples` directory. |
|[loopback-component-storage](https://github.com/strongloop/loopback-component-storage) |LoopBack 2.0 examples are in the `examples` directory.  |
|[loopback-example-APIClientApp](https://github.com/strongloop/loopback-example-apiclientapp)|iOS client example|
|[loopback-example-angular](https://github.com/strongloop/loopback-example-angular) |A simple "to do" list using AngularJS on the client and LoopBack on the server.|
|[loopback-example-app](https://github.com/strongloop/loopback-example-app)  |A full-stack LoopBack application (iCars).|
|[loopback-example-boot-scripts](https://github.com/strongloop/loopback-example-boot-scripts)|How to use the LoopBack boot script generator. |
|[loopback-example-isomorphic](https://github.com/strongloop/loopback-example-isomorphic)    |Using the LoopBack API on both client and server.|
|[loopback-example-mixins](https://github.com/strongloop/loopback-example-mixins) | Loading mixins from  directories and modules and performing different actions like observing changes and adding model attributes.   
|[loopback-example-pubsub](https://github.com/strongloop/loopback-example-pubsub) |Example using strong-pubsub |
|[loopback-example-offline-sync](https://github.com/strongloop/loopback-example-offline-sync)|Offline sync with Loopback |
|[loopback-example-passport](https://github.com/strongloop/loopback-example-passport) |PassportJS with Loopback  |
|[loopback-example-recipes](https://github.com/strongloop/loopback-example-recipes)  | Sample recipes  demonstrating LoopBack use patterns.  **NOTE**: Work-in-progress   |
|[loopback-example-remote](https://github.com/strongloop/loopback-example-remote) |How to use the LoopBack remote connector.  **NOTE**: Work-in-progress  |
|[loopback-example-ssl](https://github.com/strongloop/loopback-example-ssl)  |SSL with LoopBack   
|[strong-gatway-demo](https://github.com/strongloop/strong-gateway-demo) |OAuth2 with StrongLoop API Gateway

**Examples on docs.strongloop.com**:

- [Creating a LoopBack iOS app: part one](http://docs.strongloop.com/display/LB/Creating+a+LoopBack+iOS+app:+part+one)
- [Creating a LoopBack iOS app: part two](http://docs.strongloop.com/display/LB/Creating+a+LoopBack+iOS+app:+part+two)
- [Push notifications](http://docs.strongloop.com/display/LB/Tutorial:+Push+notifications)

##FAQ Tutorials

Example repositories for frequently-asked questions.

- [loopback-faq-email](https://github.com/strongloop/loopback-faq-email)
- [loopback-faq-middleware](https://github.com/strongloop/loopback-faq-middleware)
- [loopback-faq-operation-hooks](https://github.com/strongloop/loopback-faq-operation-hooks)
- [loopback-faq-rest-connector](https://github.com/strongloop/loopback-faq-rest-connector)
- [loopback-faq-user-management](https://github.com/strongloop/loopback-faq-user-management)
- [loopback-faq-model-relations](https://github.com/strongloop/loopback-faq-model-relations) - WIP
- [loopback-faq-build-automation](https://github.com/strongloop/loopback-faq-build-automation) - WIP

##Community examples

These are examples contributed by the LoopBack community. Let us know if you have an example to
contribute and we'll send you some swag in return for your efforts!

- [loopback-angular-admin](https://github.com/beeman/loopback-angular-admin)
- [loopback-examples-ios](https://github.com/strongloop-community/loopback-examples-ios)
- [loopback-example-user-organization](https://github.com/strongloop-community/loopback-example-user-organization)

##Deprecated examples

###LoopBack 1.x examples

These examples have not been updated for LoopBack 2.x.

- [loopback-component-example-office-supplies](https://github.com/strongloop/loopback-example-office-supplies)
- [sample-applications](https://github.com/strongloop-community/sample-applications)
- [loopback-example-proxy](https://github.com/strongloop/loopback-example-proxy)

###Other deprecated examples

These are either outdated or replaced with better examples.

- [loopback-example-angular-starter](https://github.com/strongloop/loopback-example-angular-starter) replaced with [loopback-example-angular](http://github.com/strongloop/loopback-example-angular)
- [loopback-example-coffee-shop](https://github.com/strongloop/loopback-example-coffee-shop) replaced with [loopback-getting-started-intermediate](http://github.com/strongloop/loopback-getting-started-intermediate)
- [loopback-example-customAPI](https://github.com/strongloop/loopback-example-customAPI) replaced with [loopback-getting-started](http://github.com/strongloop/loopback-getting-started)
- [loopback-example-full-stack](https://github.com/strongloop/loopback-example-full-stack) renamed to [loobpack-example-offline-sync](https://github.com/strongloop/loopback-example-offline-sync)
- [loopback-example-datasourceAPI](https://github.com/strongloop/loopback-example-datasourceAPI) replaced with [loopback-getting-started](http://github.com/strongloop/getting-started)
- [loopback-example-database](https://github.com/strongloop/loopback-example-database) replaced with 5 separate repos:
    - [loopback-example-mongodb](https://github.com/strongloop/loopback-example-mongodb)
    - [loopback-example-mssql](https://github.com/strongloop/loopback-example-mssql)
    - [loopback-example-mysql](https://github.com/strongloop/loopback-example-mysql)
    - [loopback-example-postgresql](https://github.com/strongloop/loopback-example-postgresql)
    - [loopback-example-oracle](https://github.com/strongloop/loopback-example-oracle)
- [loopback-example-extendedAPI](https://github.com/strongloop/loopback-example-extendedAPI) replaced with [loopback-getting-started](http://github.com/strongloop/loopback-getting-started)
- [loopback-example-relations-basic](https://github.com/strongloop/loopback-example-relations-basic) replaced with [loopback-example-model-relations](http://github.com/strongloop/loopback-example-model-relations)
- [loopback-example-model-relations](https://github.com/strongloop/loopback-example-model-relations) replaced with [loopback-example-relations](http://github.com/strongloop/loopback-example-relations)
- [loopback-example-mySimpleAPI](https://github.com/strongloop/loopback-example-mySimpleAPI) replaced with [loopback-getting-started](http://github.com/strongloop/loopback-getting-started)

##Terminology

These are terms and definitions used in all demos:

Term|Definition
:--|:--
App|Short for "application", in most cases this means the current demo being viewed
Docs|Short for "documentation", in most cases this refers to the [official documentation](http://docs.strongloop.com/display/LB/LoopBack)
Demo|Short for "demonstration", examples and tutorials are both considered "demos"
Deps|Short for "dependencies"
Dir|Short for "directory"
Doc|Short for "documentation", usually refers to [docs.strongloop.com](http://docs.strongloop.com)
Example|Source code and basic instructions on how to run the demo app, does not include step-by-step instructions
|Info|Short for "information"
|Repo|Short for "repository", in most cases it refers to a "GitHub" repository
|Tutorial|Includes step-by-step instructions on how to build the example app
|WIP|Short for "work in progress", meaning either some of the source code is missing or the instructions may not be complete

[loopback]: https://strongloop.com/node-js/loopback-framework/
[strongloop]: https://strongloop.com/
