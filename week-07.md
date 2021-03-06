# Week Seven

## Topic Outline

### Day 1

1. MV* Pattern
  * Models, views, controllers
  * ViewModels vs controllers
1. What is Angular?
  * History, current maintenance, v2
  * Philosophy
1. Hello World
  * Setup: HTML, module, expression, Bootstrap
1. Controllers and scoped data
  * Purpose
  * ng-controller (`as`)
  * Using `this` (controllers as instances)
  * Expressions with data
  * Methods
1. Directives (built-in)
  * Purpose
  * `ng-app` and `ng-controller`
  * Data collections and `ng-repeat`
  * `ng-show` and `ng-hide`
1. Basic filters
  * currency, date, orderBy

Homework: Shopular

### Day 2

1. Review Angular setup
1. Using ng-cloak to prevent flashing
1. Nested controllers
  * Accessing parent data in HTML and in controllers
1. Data binding
  * Forms, validation, and ng-model
  * Two-way (discuss expense)
  * `ng-submit`
1. Using `ng-click`
1. Exercise

Homework: Shopular with add item form, validation, sort (?)

### Day 3

1. Services
  * Factory pattern
  * Services as singletons
  * Dependency injection (into services and with services)
1. Built-in services
  * `$document`, `$location`, `$q`
  * jQuery Lite
1. Code organization and style guides
1. Basic testing setup (_if time_)
  * Karma, Grunt
  * Sanity check
  * Testing a simple service

Homework: Shop service

### Day 4

1. Testing Angular
  * Using Karma
  * Setting up Grunt
  * Sanity check test
1. Testing services
  * Injecting
  * Using `$rootScope.$digest()` to complete promises
1. Testing controllers
  * Using `$controller` provider
  * Mocking and injecting services
1. Adding code coverage (_if time, or on Friday_)
  * Basic principle
  * Configuration with Karma

Homework: Angular TODOs (with tests)
