# schnie

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## Learning 

workflow / build 

- https://github.com/vuejs-templates/webpack/blob/master/docs/SUMMARY.md
- http://vuejs-templates.github.io/webpack/

vue basics

https://vuejs.org/v2/guide/

register components - global or local:
https://vuejs.org/v2/guide/components.html#Registration

what we used today, interesting idea of having components even "dynamic":
https://vuejs.org/v2/guide/components.html#Dynamic-Components

we need to understand how to architect components:
https://vuejs.org/v2/guide/components.html#Authoring-Reusable-Components

Here the single file component example- how components should look like:
https://vuejs.org/v2/guide/single-file-components.html
The vue-loader is helping to easy write .vue files / components:
http://vue-loader.vuejs.org/en/

Also really important - let us roughly define and write down our requirements and test them 
BDD: http://nightwatchjs.org/guide#using-nightwatch
Units: https://vuejs.org/v2/guide/unit-testing.html

Design decision - do we need this? I think this would need deeper integration with symfony, quite some work ...
https://vuejs.org/v2/guide/ssr.html



vue tools

- http://vue-loader.vuejs.org/en/
- http://router.vuejs.org/en/
- http://vuex.vuejs.org/en/
- https://github.com/vuejs/awesome-vue

testing

- http://nightwatchjs.org/guide#using-nightwatch


Symfony integration

- https://github.com/mariusbalcytis/webpack-bundle
- Optional keep backend and frontend completely seperated.

- backend rendered pages (twig pages)
  - impressum 
  - about
  - authentication
  - ...
  - frontend integration point
    - single page vue app


## Setup with vue-cli

```
npm install -g vue-cli
vue init webpack schnie


  This will install Vue 2.x version of the template.

  For Vue 1.x use: vue init webpack#1.0 schnie

Project name? schnie
Project description? A Vue.js project
Author? felixboehm <felix@owncloud.com>
Vue build? standalone
Use ESLint to lint your code? Yes
Pick an ESLint preset? AirBNB
Setup unit tests with Karma + Mocha? Yes
Setup e2e tests with Nightwatch? Yes

   vue-cli · Generated "schnie".

   To get started:
   
     cd schnie
     npm install
     npm run dev
   
   Documentation can be found at https://vuejs-templates.github.io/webpack

```
