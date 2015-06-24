#loopback-demo

This is a [LoopBack][loopback] [demo](#terminology) list maintained by [StrongLoop][strongloop].

- [Overview](#overview)
- [Terminology](#terminology)
- [Tutorials](#tutorials)
  - [FAQ](#faq-examples)
  - [Community](#community-examples)
- [Examples](#examples)
  - [Community](#community-examples)
- [Deprecated demos](#deprecated-examples)

##Overview

The purpose of this repo is to have a single source of truth for all demos
related to LoopBack. Before starting any demos, make sure you:

- Verify the demo exists in one of our sections (if it's not in any section, then its not an official demo maintained by us)
- Verify the demo does not exist in the [deprecated section](deprecated-demos)
- Familiar yourself with the [terminology](#terminology) we use in all demos

We recommend you complete each ["Getting started" tutorial](#getting-started)
tutorial in the prescribed order. After that, feel free to try our any other
demo in any order.

###Terminology

These are terms and definitions used in all of our demos:

Term|Definition
:--|:--
App|Short for "application", in most cases this means the current demo being viewed
Demo|Short for "demonstration", examples and tutorials are both considered "demos"
Doc|Short for "documentation", usually refers to [http://docs.strongloop.com](docs.strongloop.com)
Example|Source code and basic instructions on how to run the demo app, does not include step-by-step instructions
|Info|Short for "information"
|Repo|Short for "repository", in most cases it refers to a "GitHub" repository
|Tutorial|Includes step-by-step instructions on how to build the demo app
|WIP|Short for "work in progress", meaning either some of the source code is missing or the instructions may not be complete

##Tutorials

Status|Name|Description
:-:|:--|:--
WIP|[loopback-getting-started](https://github.com/strongloop/loopback-getting-started)|A basic demo on how to use LoopBack

##Examples

Status|Name|Description
:-:|:--|:--
WIP|[loopback-getting-started-intermediate](https://github.com/strongloop/loopback-getting-started-intermediate)|A full-stack example built off of `loopback-getting-started` used to demonstrate intermediate level features of LoopBack

##Tutorial series

Each repository contains a complete application, along with step-by-step instructions to recreate it 
in the README.

Complete these in the order listed below.  When a step contains multiple repositories, you need only follow 
one of them before going to the next step; you don't have to finish all of them. For example, follow  `loopback-example-mysql` in step one, then go to step two.

###The basics

Teaches the basics on models, connectors, datasources, automigration and
discovery.

- [loopback-example-mongodb](https://github.com/strongloop/loopback-example-mongodb)
- [loopback-example-mssql](https://github.com/strongloop/loopback-example-mssql)
- [loopback-example-mysql](https://github.com/strongloop/loopback-example-mysql)
- [loopback-example-postgresql](https://github.com/strongloop/loopback-example-postgresql)
- [loopback-example-oracle](https://github.com/strongloop/loopback-example-oracle)

###Relations and filters

Teaches the basics of model relations and basic filtering via REST.

- [loopback-example-relations](https://github.com/strongloop/loopback-example-relations)

###Adding application logic

Teaches the basics of remote methods, remote hooks, model hooks, boot scripts, and middleware.

- [loopback-example-app-logic](https://github.com/strongloop/loopback-example-app-logic)

###Access control

- [loopback-example-access-control](https://github.com/strongloop/loopback-example-access-control)

##Topic-specific examples

You can follow these examples in any order since they are self-contained and specific
to a particular topic.

|WIP|Name                                                                                        |Description                                                                           |
|:-:|:-------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------|
|   |[loopback-component-push](https://github.com/strongloop/loopback-component-push)            |LoopBack 2.x examples available in the `examples` dir                                 |
|   |[loopback-component-storage](https://github.com/strongloop/loopback-component-storage)      |LoopBack 2.0 examples available in the `examples` dir                                 |
|   |[loopback-example-APIClientApp](https://github.com/strongloop/loopback-example-apiclientapp)|iOS client example                                                                                      |
|   |[loopback-example-angular](https://github.com/strongloop/loopback-example-angular)          |A simple todo list using AngularJS on the client side and LoopBack on the server side.|
|   |[loopback-example-app](https://github.com/strongloop/loopback-example-app)                  |A full stack LoopBack application (iCars)                                             |
|   |[loopback-example-boot-scripts](https://github.com/strongloop/loopback-example-boot-scripts)|How to use the LoopBack boot script generator                                         |
|   |[loopback-example-isomorphic](https://github.com/strongloop/loopback-example-isomorphic)    |Using LoopBack on the client-side and server-side.                                    |
|   |[loopback-example-pubsub](https://github.com/strongloop/loopback-example-pubsub)            |Example using strong-pubsub                                                                                      |
|   |[loopback-example-offline-sync](https://github.com/strongloop/loopback-example-offline-sync)|Offline sync with Loopback                                                            |
|   |[loopback-example-passport](https://github.com/strongloop/loopback-example-passport)        |PassportJS with Loopback                                                              |
| ✔ |[loopback-example-recipes](https://github.com/strongloop/loopback-example-recipes)          |                                                                                      |
| ✔ |[loopback-example-remote](https://github.com/strongloop/loopback-example-remote)            |How to use the LoopBack remote connector                                              |
|   |[loopback-example-ssl](https://github.com/strongloop/loopback-example-ssl)                  |SSL with LoopBack                                                                     |

**Examples on docs.strongloop.com**:

- [Creating a LoopBack iOS app: part one](http://docs.strongloop.com/display/LB/Creating+a+LoopBack+iOS+app:+part+one)
- [Creating a LoopBack iOS app: part two](http://docs.strongloop.com/display/LB/Creating+a+LoopBack+iOS+app:+part+two)
- [Push notifications](http://docs.strongloop.com/display/LB/Tutorial:+Push+notifications)

##FAQ examples

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

### Other deprecated examples

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

[loopback]: https://strongloop.com/node-js/loopback-framework/
[strongloop]: https://strongloop.com/
