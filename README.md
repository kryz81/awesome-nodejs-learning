# Awesome Node.js Learning Resources

---

## Contents

- [Awesome Node.js Learning Resources](#awesome-nodejs-learning-resources)
  - [Contents](#contents)
  - [Node.js History](#nodejs-history)
  - [Module System](#module-system)
  - [Patterns, Antipatterns](#patterns-antipatterns)
  - [Reactor Pattern](#reactor-pattern)
  - [Node.js Internals](#nodejs-internals)
  - [Event Loop](#event-loop)
  - [Streams](#streams)
  - [Event System](#event-system)
  - [Handling Errors](#handling-errors)
  - [Testing](#testing)
  - [Debugging](#debugging)
  - [Linting and formatting](#linting-and-formatting)
  - [Optimizing Performance](#optimizing-performance)
  - [Security](#security)
  - [Logging](#logging)
  - [Authentication](#authentication)
  - [Websockets](#websockets)
  - [Node.js with docker](#nodejs-with-docker)
  - [Node.js with typescript](#nodejs-with-typescript)
  - [Deployment](#deployment)
  - [Monitoring](#monitoring)
  - [Frameworks](#frameworks)
  - [Architecture and Project Structure](#architecture-and-project-structure)
  - [Native Modules](#native-modules)
  - [NPM](#npm)
  - [Other](#other)
  - [Recommended Books](#recommended-books)
  - [Recommended courses](#recommended-courses)

---

## Node.js History

- [Original Node.js Presentation by Ryan Dahl](https://www.youtube.com/watch?v=ztspvPYybIY)
- [History of Node.js on a Timeline](https://blog.risingstack.com/history-of-node-js/)

## Module System

- [What is a difference between a module and a package](https://stackoverflow.com/questions/20008442/difference-between-a-module-and-a-package-in-node)
- [Getting started with Node.js modules](https://adrianmejia.com/getting-started-with-node-js-modules-require-exports-imports-npm-and-beyond/)
- [Requiring modules in Node.js: Everything you need to know](https://www.freecodecamp.org/news/requiring-modules-in-node-js-everything-you-need-to-know-e7fbd119be8/)

## Patterns, Antipatterns

- [Fundamental Node.js Design Patterns](https://blog.risingstack.com/fundamental-node-js-design-patterns/)
- [9 Ways to Avoid Pitfalls Using Node.js](https://blog.avenuecode.com/9-ways-to-avoid-pitfalls-using-nodejs)

## Reactor Pattern

- [Understanding Reactor Pattern](https://dzone.com/articles/understanding-reactor-pattern-thread-based-and-eve)
- [Understanding Reactor Pattern for Highly Scalable I/O Bound Web Server](https://www.puncsky.com/blog/2015/01/13/understanding-reactor-pattern-for-highly-scalable-i-o-bound-web-server/)

## Node.js Internals

- [Crossing the JS/C++ Boundary — Advanced NodeJS Internals](https://blog.insiderattack.net/crossing-the-js-c-boundary-advanced-nodejs-internals-part-1-cb52957758d8)
- [Internals of Node- Advance node](https://medium.com/front-end-weekly/internals-of-node-advance-node-%EF%B8%8F-8612f6a957d7)
- [https://codeburst.io/node-js-v8-internals-an-illustrative-primer-83766e983bf6](https://codeburst.io/node-js-v8-internals-an-illustrative-primer-83766e983bf6)
- [Nodejs C++/JS Boundary: Crossing The Rubicon](https://blog.bitsrc.io/nodejs-c-js-boundary-crossing-the-rubicon-c9c5511907a2)

## Event Loop

- [Event Loop and the Big Picture](https://blog.insiderattack.net/event-loop-and-the-big-picture-nodejs-event-loop-part-1-1cb67a182810)
- [Timers, Immediates and Next Ticks](https://blog.insiderattack.net/timers-immediates-and-process-nexttick-nodejs-event-loop-part-2-2c53fd511bb3)
- [Promises, Next Ticks and Immediates](https://blog.insiderattack.net/promises-next-ticks-and-immediates-nodejs-event-loop-part-3-9226cbe7a6aa)
- [Handling IO with Event Loop](https://blog.insiderattack.net/handling-io-nodejs-event-loop-part-4-418062f917d1)
- [Event Loop Best Practices](https://blog.insiderattack.net/event-loop-best-practices-nodejs-event-loop-part-5-e29b2b50bfe2)
- **[New Changes to the Timers and Microtasks in Node v11.0.0](https://blog.insiderattack.net/new-changes-to-timers-and-microtasks-from-node-v11-0-0-and-above-68d112743eb3)**
- [The Event Loop](https://developer.ibm.com/tutorials/learn-nodejs-the-event-loop/)
- [A complete guide to the Node.js event loop](https://blog.logrocket.com/a-complete-guide-to-the-node-js-event-loop/)
- [What you should know to really understand the Node.js Event Loop](https://medium.com/the-node-js-collection/what-you-should-know-to-really-understand-the-node-js-event-loop-and-its-metrics-c4907b19da4c)
- [The Node.js Event Loop](https://flaviocopes.com/node-event-loop/)

## Streams

- [Stream Handbook by substack](https://github.com/substack/stream-handbook)
- [Node.js Streams: Everything you need to know](https://www.freecodecamp.org/news/node-js-streams-everything-you-need-to-know-c9141306be93/)
- [Node.js Streams](https://flaviocopes.com/nodejs-streams/)
- [Node.js Streams Demystified](https://codeburst.io/nodejs-streams-demystified-e0b583f0005)
- [Node.js File Streams Explained](https://areknawo.com/node-js-file-streams-explained/)

## Event System

- [Event-Driven Programming in Node.js](https://alligator.io/nodejs/event-driven-programming/)
- [How to code your own event emitter in Node.js](https://www.freecodecamp.org/news/how-to-code-your-own-event-emitter-in-node-js-a-step-by-step-guide-e13b7e7908e1/)
- [Handling and dispatching events with Node.js](https://blog.logrocket.com/handling-and-dispatching-events-with-node-js/)

## Handling Errors

- [Error Management in Node.js Applications](https://blog.insiderattack.net/error-management-in-node-js-applications-e43198b71663)
- [Error handling - The missing piece of your node.js architecture](https://softwareontheroad.com/error-handling-nodejs/)

## Testing

- [Unit Testing Express Middleware Behavior](https://medium.com/@morrissinger/unit-testing-express-middleware-behavior-in-ecmascript-2015-f1641ebb8040)
- [A testing guide for Express with request and response mocking/stubbing using Jest or sinon](https://codewithhugo.com/express-request-response-mocking/)
- [Unit testing in Express with Promise-based Middleware and Controllers](https://codeburst.io/unit-testing-in-express-with-promise-based-middleware-and-controllers-7d3d59ae61f8)

## Debugging

- [How to Debug a Node.js app in a Docker Container](https://blog.risingstack.com/how-to-debug-a-node-js-app-in-a-docker-container/)

## Linting and formatting

## Optimizing Performance

## Security

- [We’re under attack! 23+ Node.js security best practices](https://medium.com/@nodepractices/were-under-attack-23-node-js-security-best-practices-e33c146cb87d)

## Logging

- [Getting Started With morgan](https://alligator.io/nodejs/getting-started-morgan/)

## Authentication

- [Learn how to handle authentication with Node using Passport.js](https://www.freecodecamp.org/news/learn-how-to-handle-authentication-with-node-using-passport-js-4a56ed18e81e/)
- [Your Node.js authentication tutorial is (probably) wrong](https://hackernoon.com/your-node-js-authentication-tutorial-is-wrong-f1a3bf831a46)

## Websockets

- [Introduction to Socket.IO](https://alligator.io/nodejs/intro-to-socketio/)

## Node.js with docker

## Node.js with typescript

## Deployment

## Monitoring

## Frameworks

- [An introduction to the hapi Node.js Framework](https://alligator.io/nodejs/intro-to-hapi/)
- [Serving Static Files in Express.js](https://alligator.io/nodejs/serving-static-files-in-express/)

## Architecture and Project Structure

- [Bulletproof node.js project architecture ](https://softwareontheroad.com/ideal-nodejs-project-structure/)

## Native Modules

## NPM

- [These NPM tricks will make you a pro](https://www.freecodecamp.org/news/10-npm-tricks-that-will-make-you-a-pro-a945982afb25/)
- [NPM Task Running Techniques](https://medium.com/netscape/npm-task-running-techniques-15fe5b697f15)
- [4 Solutions To Run Multiple Node.js or NPM Commands Simultaneously](https://itnext.io/4-solutions-to-run-multiple-node-js-or-npm-commands-simultaneously-9edaa6215a93)

## Other

- [Running Multiple Versions of Node.js with Node Version Manager](https://alligator.io/nodejs/node-version-manager/)
- [Want to be a Web Developer? Learn Node.js not PHP](https://medium.com/zerotomastery/want-to-be-a-web-developer-learn-node-js-not-php-dc298154fafd)
- [The leftpad incident](https://blog.npmjs.org/post/141577284765/kik-left-pad-and-npm)

## Recommended Books

- **[Node.js Design Patterns](https://www.packtpub.com/web-development/nodejs-design-patterns-second-edition)** (must-read for every node.js dev)
- [Node Cookbook](https://www.packtpub.com/catalogsearch/result/?q=node%20cookbook)

## Recommended courses

- [Node.js: Advanced Concepts](https://www.udemy.com/advanced-node-for-developers/)
