# Awesome CoffeeScript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome CoffeeScript frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
	* [Version Control](#version-control)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Frontend and UI Components](#frontend-and-ui-components)
	* [Web Servers and Proxies](#web-servers-and-proxies)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
* Machine Learning and AI
	* [Computer Vision](#computer-vision)
	* [Natural Language Processing](#natural-language-processing)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [Mobile](#mobile)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Text Processing](#text-processing)
	* [Date and Time](#date-and-time)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Business and Domain
	* [Finance and Trading](#finance-and-trading)
	* [Business and Productivity](#business-and-productivity)
* Science and Math
	* [Scientific Computing](#scientific-computing)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [codecombat/codecombat](https://github.com/codecombat/codecombat) - Game for learning how to code.
* [osscafe/gulp-cheatsheet](https://github.com/osscafe/gulp-cheatsheet) - A cheatsheet for gulp.js
* [autotelicum/Smooth-CoffeeScript](https://github.com/autotelicum/Smooth-CoffeeScript) - A book on functional programming in CoffeeScript
* [ecomfe/knowledge](https://github.com/ecomfe/knowledge) - Front-end knowledge hierarchy
* [koba04/vuejs-book](https://github.com/koba04/vuejs-book) - This book is vue.js guide book. *(archived)*
* [michikono/slackbot-tutorial](https://github.com/michikono/slackbot-tutorial) - Tutorial on how to write slack bots and scripts
* [noonat/intersect](https://github.com/noonat/intersect) - An explanation of 2D collision tests in JavaScript
* [zerowidth/jps-explained](https://github.com/zerowidth/jps-explained) - Code for a "Jump Point Search, Explained" post on zerowidth.com
* [markbates/Programming-In-CoffeeScript](https://github.com/markbates/Programming-In-CoffeeScript) - Source code for the Programming in CoffeeScript book.
* [adamjspooner/coffeescript-meet-backbonejs](https://github.com/adamjspooner/coffeescript-meet-backbonejs) - An introduction to Backbone.js using CoffeeScript.
* [edemaine/coffeescript-for-python](https://github.com/edemaine/coffeescript-for-python) - CoffeeScript for Python programmers (a guide)
* [ovcharik/meteor-getting-started](https://github.com/ovcharik/meteor-getting-started) - Урок для хабры. Разработка первого метеор приложения.
* [boundvariable/coffeescript-in-action](https://github.com/boundvariable/coffeescript-in-action) - Source code for the Manning book CoffeeScript in Action
* [jaigouk/nodetuts-coffeescript](https://github.com/jaigouk/nodetuts-coffeescript) - Coffeescript version of nodetuts *(archived)*
* [spbooks/COFFEESCRIPT1](https://github.com/spbooks/COFFEESCRIPT1) - Jump Start CoffeeScript, code archive

### Examples and Exercises

* [CaryLandholt/AngularFun](https://github.com/CaryLandholt/AngularFun) - AngularJS Reference Architecture
* [twilson63/express-coffee](https://github.com/twilson63/express-coffee) - A Template for NodeJs Application using Express, CoffeeScript, Jade, Stylus, Nib
* [atom-archive/electron-starter](https://github.com/atom-archive/electron-starter) - Example Electron app *(archived)*
* [robotdestroy/Framer-Snippets-Library](https://github.com/robotdestroy/Framer-Snippets-Library) - A library of Framer snippets to help speed up your workflow
* [jamis/csmazes](https://github.com/jamis/csmazes) - Maze algorithms implemented in CoffeeScript, with an eye toward demonstrating how the algorithms work by animating them.
* [sleepyfox/coffeescript-koans](https://github.com/sleepyfox/coffeescript-koans) - Koans: learn CoffeeScript by doing it
* [yogiben/meteor-starter](https://github.com/yogiben/meteor-starter) - Kickstart your meteor projects
* [carbonfive/vimtronner](https://github.com/carbonfive/vimtronner) - A multi-player Vim trainer.
* [fbsamples/graph-api-webhooks-samples](https://github.com/fbsamples/graph-api-webhooks-samples) - These are sample clients for Facebook's Graph API Webhooks and Instagram's Real-time Photo Updates API. *(archived)*
* [derbyjs/derby-examples](https://github.com/derbyjs/derby-examples) - Example applications for the Derby framework
* [brunch/brunch-with-chaplin](https://github.com/brunch/brunch-with-chaplin) - Boilerplate application for Brunch with Chaplin framework included. *(archived)*
* [KyleAMathews/coffee-react-quickstart](https://github.com/KyleAMathews/coffee-react-quickstart) - Quickstart for building React single page apps using Coffeescript, Gulp, Webpack, and React-Router
* [aluxian/electron-superkit](https://github.com/aluxian/electron-superkit) - :zap: An Electron starter kit with super powers. :zap: *(archived)*
* [maccman/spine.contacts](https://github.com/maccman/spine.contacts) - Spine demo contact manager
* [nylas/component-store-example](https://github.com/nylas/component-store-example) - An example of the topics covered in Building for Plugins with React & Flux
* [johnthethird/react-starter-template](https://github.com/johnthethird/react-starter-template) - React (reactjs), Gulp, Webpack, Bootstrap, LiveReload, all tied up in a bow.
* [iroy2000/react-reflux-boilerplate-with-webpack](https://github.com/iroy2000/react-reflux-boilerplate-with-webpack) - React + Reflux + CoffeeScript + Stylus Boilerplate with Webpack
* [kbroman/d3examples](https://github.com/kbroman/d3examples) - Examples of interactive graphics using d3.js
* [khaled/react-express-template](https://github.com/khaled/react-express-template) - Full stack web app starter template using React, ES6, CoffeeScript, Express, and more
* [nylas/inbox-scaffold-html5](https://github.com/nylas/inbox-scaffold-html5) - The Inbox HTML5 App Scaffold - a foundation for building great mail apps. *(archived)*
* [mutewinter/tapas-with-ember](https://github.com/mutewinter/tapas-with-ember) - 🚫 UNMAINTAINED: A Brunch skeleton for rapid Ember development. Including Ember installation scripts, environment-specific JS builds, generators, and Ember.vim support. *(archived)*
* [hjr265/toptal-recommengine](https://github.com/hjr265/toptal-recommengine) - Prototype recommendation engine built to accompany an article on Toptal Blog
* [elving/brunch-with-hipsters](https://github.com/elving/brunch-with-hipsters) - Brunch with Hipsters is a rad Brunch app skeleton that comes with unicorns out of the box.
* [glebm/gulp-webpack-react-bootstrap-sass-template](https://github.com/glebm/gulp-webpack-react-bootstrap-sass-template) - Web App Client Template: React. Sass, Coffee, JSX. Bootstrap for Sass. Compiled with Gulp and Webpack. *(archived)*
* [ericclemmons/genesis-skeleton](https://github.com/ericclemmons/genesis-skeleton) - Modern, opinionated, full-stack starter kit for rapid, streamlined application development.
* [meilisearch/demos](https://github.com/meilisearch/demos) - A list of Meilisearch demos with open-source code and live preview ⚡️
* [twilson63/cakefile-template](https://github.com/twilson63/cakefile-template) - This is a cakefile template for coffeescript, docco and mocha
* [zmaril/d3.js-boilerplate](https://github.com/zmaril/d3.js-boilerplate) - Boilerplate to help speed up d3.js development
* [brikis98/node-backbone-skeleton](https://github.com/brikis98/node-backbone-skeleton) - A skeleton project for creating applications that use node.js server-side, backbone.js client-side, underscore.js templates, CoffeeScript as a JS pre-processor and Compass/SASS as a CSS pre-processor..
* [systemseed/drupal_reactjs_boilerplate](https://github.com/systemseed/drupal_reactjs_boilerplate) - Docker based Drupal / React boilerplate with Unit / API / End-to-end test coverage examples.
* [appleboy/html5-template-engine](https://github.com/appleboy/html5-template-engine) - html5 template engine with CoffeeScript, Compass, RequireJS.
* [chaplinjs/chaplin-boilerplate](https://github.com/chaplinjs/chaplin-boilerplate) - Boilerplate application for the Chaplin.js library *(archived)*
* [jeffling/angular-webpack-example](https://github.com/jeffling/angular-webpack-example) - This is sort of a shrine to what was cutting edge front-end in 2014. Simple template with webpack (run from gulp) that supports angular (from bower), with some common settings.
* [minimal-xyz/minimal-webpack-nodejs-hmr](https://github.com/minimal-xyz/minimal-webpack-nodejs-hmr) - Webpack Backend HMR Demo
* [roytruelove/angular-grunt-coffeescript](https://github.com/roytruelove/angular-grunt-coffeescript) - Seed project for large CoffeeScript AngularJS projects
* [naoya/boilerplate](https://github.com/naoya/boilerplate) - Application boilerplate for something *(archived)*
* [dweldon/frappe](https://github.com/dweldon/frappe) - template for creating express applications with coffeescript
* [ichord/angular-coffee-AMD-seed](https://github.com/ichord/angular-coffee-AMD-seed) - angular coffeescript requirejs
* [eunjae-lee/node-express-grunt-boilerplate](https://github.com/eunjae-lee/node-express-grunt-boilerplate) - A boilerplate to start a new express project based on CoffeeScript, Grunt build system, forever runner, Jade Template Engine and bootstrap
* [searls/try-jasmine](https://github.com/searls/try-jasmine) - An online sandbox for playing with Jasmine, a bunch of supporting scripts, and Backbone/Underscore/CoffeeScript
* [wmora/angular-espresso](https://github.com/wmora/angular-espresso) - Based on angular-seed, a starting point for writing an AngularJS app running on an Express backend, written in CoffeeScript *(archived)*
* [jamesdwilson/meteor-jw-opinionated-skeleton](https://github.com/jamesdwilson/meteor-jw-opinionated-skeleton) - ABANDONED: A collection of packages and a good starting point for building my next meteor project. You might like it too. :) Coffeescript based *(archived)*
* [adamalbrecht/angular-starter-kit](https://github.com/adamalbrecht/angular-starter-kit) - An opinionated starter template for crafting single-page web applications using Angular.js, Coffeescript, SCSS, Jade, Bootstrap, UI-Router, Font-Awesome and a few other carefully picked tools.
* [BrunoRB/algorithms.coffee](https://github.com/BrunoRB/algorithms.coffee) - Classic algorithms and data structures in coffeescript. Making the World a better place, with coffee.
* [iampeter/backbone-marionette-gulp-seed](https://github.com/iampeter/backbone-marionette-gulp-seed) - A seed project using Backbone.js, Marionette.js, Twitter Bootstrap 3, Stylus, Jade and Coffeescript all bundled with Gulp.js
* [olafurnielsen-zz/form5-node-express-mongoose-coffeescript](https://github.com/olafurnielsen-zz/form5-node-express-mongoose-coffeescript) - A Node.js skeleton using Express, Mongoose and Coffeescript.
* [jamescarr/nodejs-mongodb-blog](https://github.com/jamescarr/nodejs-mongodb-blog) - Tutorial app for using node.js, coffeescript and mongodb
* [f/phaser-coffee-boilerplate](https://github.com/f/phaser-coffee-boilerplate) - Phaser CoffeeScript + Browserify + LiveReload Boilerplate
* [nbartlomiej/coffee-guard-caat-jessie](https://github.com/nbartlomiej/coffee-guard-caat-jessie) - CAAT & CoffeeScript & Jessie & Guard application template
* [maxatwork/expressjs_template](https://github.com/maxatwork/expressjs_template) - Node + ExpressJS + Coffeescript + Stylus + Twitter bootstrap + Jade + assets pipeline + Mocha + Should + Supertest project template.
* [tomblomfield-zz/meteor-chat](https://github.com/tomblomfield-zz/meteor-chat) - Simple chat application using Meteor JS and Coffeescript
* [huytd/coffee-now](https://github.com/huytd/coffee-now) - ☕ CoffeeScript Playground
* [phenome/generator-lean-mean](https://github.com/phenome/generator-lean-mean) - Yeoman generator. MEAN stack. Coffeescript, Stylus, Jade, Gulp
* [quartzmo/mocha-coffeescript-boilerplate](https://github.com/quartzmo/mocha-coffeescript-boilerplate) - A minimalistic template for starting a CoffeeScript project based on visionmedia/mocha tests
* [tbeseda/angularjs-for-hipsters](https://github.com/tbeseda/angularjs-for-hipsters) - The AngularJS Todo app ported to CoffeeScript, Jade, and Stylus -- served with Express
* [ozankasikci/generator-phaser-coffeescript-gulp](https://github.com/ozankasikci/generator-phaser-coffeescript-gulp) - A yeoman generator for developing games with Phaser framework using coffeescript and gulp. Browserifies, coffeeifies and live reloads using browser-sync.
* [thibaultlaurens/mean.coffee](https://github.com/thibaultlaurens/mean.coffee) - coffeescript port of http://mean.io/
* [coffee-js/vue-coffee-workflow](https://github.com/coffee-js/vue-coffee-workflow) - This project demonstrates writing Vue.js 2 in plain CoffeeScript.
* [anfelor/TodoMVC-CoffeeScript-and-Vue.js](https://github.com/anfelor/TodoMVC-CoffeeScript-and-Vue.js) - A TodoMVC implementation based on the official example by Evan You - DEPRECATED based on Vue 1.0
* [MaksJS/Namespace-in-CoffeeScript](https://github.com/MaksJS/Namespace-in-CoffeeScript) - pattern to simulate namespace in coffeescript
* [the-trash/ExpressOnSteroids](https://github.com/the-trash/ExpressOnSteroids) - Node.js/Express App + CoffeeScript + SASS + JADE (HAML)
* [bfontaine/Katas](https://github.com/bfontaine/Katas) - :coffee: 27 katas in 27 languages (not only CoffeeScript, GitHub!)
* [swombat/meteor-todos-coffeescript](https://github.com/swombat/meteor-todos-coffeescript) - Todos example from Meteor JS server, converted to coffeescript, with some tidying up and tweaking
* [ouzhenkun/ionic-nodeclub](https://github.com/ouzhenkun/ionic-nodeclub) - a simple ionic starter project, use coffeescript and sass
* [SimonDegraeve/react-coffee-quickstart](https://github.com/SimonDegraeve/react-coffee-quickstart) - React/CoffeeScript project
* [swlkr/coffee-pot](https://github.com/swlkr/coffee-pot) - A boilerplate for node.js apps written in coffeescript
* [jbenet/saucer](https://github.com/jbenet/saucer) - coffeescript boilerplate
* [PEM--/hellofamousgulped](https://github.com/PEM--/hellofamousgulped) - HelloWord in Famo.us using Gulp.js, Browserify and CoffeeScript. Act as my template for Famo.us.
* [marcelinhov2/angular-kickoff](https://github.com/marcelinhov2/angular-kickoff) - AngularJS + CoffeeScript + Ng-Classify = s2

## Language and Tooling

### Compilers and Interpreters

* [jashkenas/coffeescript](https://github.com/jashkenas/coffeescript) - Unfancy JavaScript
* [js2coffee/js2coffee](https://github.com/js2coffee/js2coffee) - Compile JavaScript to CoffeeScript
* [michaelficarra/CoffeeScriptRedux](https://github.com/michaelficarra/CoffeeScriptRedux) - :sweat: rewrite of the CoffeeScript compiler with proper compiler design principles and a focus on robustness and extensibility
* [jsdf/coffee-react-transform](https://github.com/jsdf/coffee-react-transform) - DEPRECATED – Provides React JSX support for Coffeescript
* [jsdf/coffee-react](https://github.com/jsdf/coffee-react) - DEPRECATED – Unfancy JavaScript with React JSX markup
* [xixixao/Shem](https://github.com/xixixao/Shem) - The compiler of the programming language Shem
* [danielgtaylor/nesh](https://github.com/danielgtaylor/nesh) - An enhanced, extensible interactive shell for Node.js and CoffeeScript
* [int3/metajs](https://github.com/int3/metajs) - Visualize your Javascript with a CPS metacircular interpreter.
* [antonmedv/ultra-tiny-compiler](https://github.com/antonmedv/ultra-tiny-compiler) - Ultra Tiny Compiler
* [tarruda/vm.js](https://github.com/tarruda/vm.js) - Javascript bytecode compiler and VM implemented in pure coffeescript
* [jescalan/accord](https://github.com/jescalan/accord) - (unmaintained) a unified interface for compiled languages and templates in javascript
* [estools/esutils](https://github.com/estools/esutils) - utility box for ECMAScript language tools
* [fab13n/parsec-coffee-script](https://github.com/fab13n/parsec-coffee-script)
* [fabiosantoscode/js2cpp](https://github.com/fabiosantoscode/js2cpp) - A toy js -> c++ compiler written in coffeescript. Uses escodegen to write c++ and tern to figure out types.
* [sgentle/catenary](https://github.com/sgentle/catenary) - Concatenative programming for Javascript
* [kevinmehall/node-llvm](https://github.com/kevinmehall/node-llvm) - LLVM bindings for Node.JS
* [madfish-solutions/sol2ligo](https://github.com/madfish-solutions/sol2ligo) - ⌨️ 🔮 Transpiler from Solidity to PascalLIGO language
* [andreypopp/less2stylus](https://github.com/andreypopp/less2stylus) - [NOT MAINTAINED] LESS to Stylus source to source convertor capable of translating Bootstrap
* [duncansmart/coffeescript-windows](https://github.com/duncansmart/coffeescript-windows) - A shim that allows CoffeeScript to be compiled using Windows Script Host *(archived)*
* [mrluc/macros.coffee](https://github.com/mrluc/macros.coffee) - Lisp-style macros for CoffeeScript
* [michaelficarra/cscodegen](https://github.com/michaelficarra/cscodegen) - :recycle: CoffeeScript code generator
* [f/macaron](https://github.com/f/macaron) - Macros for CoffeeScript
* [mikesmullin/coffee-stylesheets](https://github.com/mikesmullin/coffee-stylesheets) - Transpiler similar to SASS/SCSS/LESS/Stylus, except its 100% CoffeeScript!
* [replit-archive/lol-coffee](https://github.com/replit-archive/lol-coffee) - A LOLCode compiler+VM in CoffeeScript
* [davidpadbury/stirred-coffee](https://github.com/davidpadbury/stirred-coffee) - Macros in CoffeeScript prototype
* [grant/javacoffee](https://github.com/grant/javacoffee) - ☕ Coffeescript-like syntax for writing Java code

### Build Systems

* [jescalan/roots](https://github.com/jescalan/roots) - a toolkit for rapid advanced front-end development
* [linemanjs/lineman](https://github.com/linemanjs/lineman) - Lineman helps you build fat-client JavaScript apps. It produces happiness by building assets, mocking servers, running specs on every file change
* [sstephenson/stitch](https://github.com/sstephenson/stitch) - Stitch your CommonJS modules together for the browser *(archived)*
* [slara/generator-reveal](https://github.com/slara/generator-reveal) - Yeoman generator for Reveal.js
* [techpines/asset-rack](https://github.com/techpines/asset-rack) - Static Web Framework for Nodejs
* [cognitom/gulp-sketch](https://github.com/cognitom/gulp-sketch) - A SketchTool plugin for gulp
* [dsimard/ready.js](https://github.com/dsimard/ready.js) - OBSOLETE - continuous javascript integration
* [anodynos/uRequire](https://github.com/anodynos/uRequire) - The Ultimate JavaScript Module Builder & Automagical Task Runner. Convert AMD & CommonJS/NodeJS modules to UMD, AMD, CommonJS or bundle them as `combined.js` (rjs & almond, AMDclean soon) & automagically run/test/watch them on nodejs, Web/AMD or Web/Script. Declarative & DRY config with inheritance. Manipulate & inject dependencies, module code, banners, version etc while building with a single line. Support two kinds of plugins, ResourceConverter (i.e file level) and AfterBuilder (i.e the whole bundle). Transparent support for Coffeescript, IcedCoffeescript, Coco, LiveScript – they’re just JavaScript :-)
* [rinh/fekit](https://github.com/rinh/fekit) - FE Toolkit
* [EtienneLem/skeleton](https://github.com/EtienneLem/skeleton) - Express 3.0 framework-less app structure generator *(archived)*
* [mdlawson/piping](https://github.com/mdlawson/piping) - Keep your code piping hot! Live code reloading without additional binaries
* [bevry-archive/buildr](https://github.com/bevry-archive/buildr) - The (Java|Coffee)Script and (CSS|Less) (Builder|Bundler|Packer|Minifier|Merger|Checker)
* [benbria/aliasify](https://github.com/benbria/aliasify) - Rewrite require calls in browserify modules.
* [livereload/livereload-extensions](https://github.com/livereload/livereload-extensions) - LiveReload Browser Extensions
* [logankoester/grunt-phonegap](https://github.com/logankoester/grunt-phonegap) - A Grunt plugin to provide local build tasks for Phonegap applications
* [scalableminds/amd-optimize](https://github.com/scalableminds/amd-optimize) - An AMD (RequireJS) optimizer that's stream-friendly. Made for gulp. *(archived)*
* [gulp-community/gulp-order](https://github.com/gulp-community/gulp-order) - This gulp plugin allows you to reorder a stream of files via globs.
* [TrevorBurnham/Jitter](https://github.com/TrevorBurnham/Jitter) - A simple CoffeeScript compilation utility
* [dsimard/grunt-angular-phonegap](https://github.com/dsimard/grunt-angular-phonegap) - Combine yeoman/generator-angular and phonegap
* [geejs/gulp-tap](https://github.com/geejs/gulp-tap) - Easily tap into a gulp pipeline without creating a plugin.
* [esamattis/piler](https://github.com/esamattis/piler) - Deprecated Asset Manager for Node.js *(archived)*
* [anaisbetts/grunt-build-atom-shell](https://github.com/anaisbetts/grunt-build-atom-shell) - Grunt task to build Electron and rebuild node modules
* [craigspaeth/nap](https://github.com/craigspaeth/nap) - Compile, manage, & package stylesheets, javascripts, and javascript templates for node.js
* [pthrasher/snockets](https://github.com/pthrasher/snockets) - Sprockets-style script concatenation for Node *(archived)*
* [pjeby/gulpsmith](https://github.com/pjeby/gulpsmith) - Use gulp plugins in Metalsmith, or Metalsmith plugins in gulp
* [fairfieldt/coffeescript-concat](https://github.com/fairfieldt/coffeescript-concat) - A utility that preprocesses and concatenates CoffeeScript source files
* [sakejs/sake-cli](https://github.com/sakejs/sake-cli) - 🍶 Sake is a build tool for JavaScript.
* [icholy/ember-brunch](https://github.com/icholy/ember-brunch)
* [elidoran/cosmos-browserify](https://github.com/elidoran/cosmos-browserify) - Browserify npm modules for client side in Meteor packages *(archived)*
* [sakejs/sake-core](https://github.com/sakejs/sake-core) - Sake's core interface.
* [debrouwere/draughtsman](https://github.com/debrouwere/draughtsman) - Transparent compilation of templates and stylesheets for prototyping HTML interfaces. Also live reloading.
* [ddollar/anvil](https://github.com/ddollar/anvil) - Generic build server *(archived)*
* [zeekay/handroll](https://github.com/zeekay/handroll) - 🍣 Expertly rolled JavaScript. CLI + library for bundling JavaScript with Rollup.js
* [benbria/browserify-transform-tools](https://github.com/benbria/browserify-transform-tools) - Utilities for writing browserify transforms.
* [ricardobeat/cake-flour](https://github.com/ricardobeat/cake-flour) - Javascript build tools
* [devongovett/importer](https://github.com/devongovett/importer) - Deprecated: File importing for CoffeeScript and JavaScript
* [CedX/PhpMinifier.js](https://github.com/CedX/PhpMinifier.js) - Minify PHP source code by removing comments and whitespace.
* [wesbos/coffeescript-growl](https://github.com/wesbos/coffeescript-growl) - Growl notifications for the Node.js CoffeeScript Compiler
* [alexspeller/ember-cli-coffees6](https://github.com/alexspeller/ember-cli-coffees6) - Makes using coffeescript nicer in ember-cli by supporting es6 syntax natively
* [duncansmart/LessCoffee](https://github.com/duncansmart/LessCoffee) - LESS and CoffeeScript HTTP handlers for ASP.NET web sites *(archived)*
* [kmalakoff/easy-bake](https://github.com/kmalakoff/easy-bake) - EasyBake enables CoffeeScript/JavaScript file-based configuration for your CoffeeScript library management needs (coffee compiling, compression, joining CoffeeScript + JavaScript files, headless testing for QUnit/Jasmine/NodeUnit, client/server version testing, etc).
* [CaryLandholt/gulp-ng-classify](https://github.com/CaryLandholt/gulp-ng-classify) - Convert CoffeeScript classes to AngularJS modules with ng-classify
* [soulwire/Coffee-Percolator](https://github.com/soulwire/Coffee-Percolator) - Use import directives in CoffeeScript to manage dependancies with this tasty CakeFile
* [thesunny/shampoo](https://github.com/thesunny/shampoo) - The ultimate browserify task. Watches files for changes. Uses a cache for super speed (instant builds). CoffeeScript supported out of box. Alias mappings. Shimming. Everything in one easy to use package.
* [marquee/proto](https://github.com/marquee/proto) - A front-end web prototyping tool, combining markup (jade), script (coffeescript/cjsx), and style (stylus), into a served single page on-the-fly.

### Package Management

* [atom/apm](https://github.com/atom/apm) - Atom Package Manager *(archived)*
* [bumped/bumped](https://github.com/bumped/bumped) - :package: Makes easy release software *(archived)*
* [keybase/node-installer](https://github.com/keybase/node-installer) - An installer/updater for the node client. *(archived)*
* [heroku/semver.io](https://github.com/heroku/semver.io) - *DEPRECATED* The semver.io instance has now been sunset: https://github.com/heroku/semver.io/issues/74 *(archived)*
* [mirek/node-unused-deps](https://github.com/mirek/node-unused-deps) - Report unused npm packages in node, es6, babel or coffee project.

### Linters and Formatters

* [kucherenko/jscpd](https://github.com/kucherenko/jscpd) - Copy/paste detector for source code. 220+ languages, Rust engine, SARIF/HTML/badge reporters, GitHub Action, MCP server for AI agents.
* [clutchski/coffeelint](https://github.com/clutchski/coffeelint) - Lint your CoffeeScript. *(archived)*
* [flosse/sloc](https://github.com/flosse/sloc) - simple tool to count SLOC (source lines of code)
* [outsideris/popularconvention](https://github.com/outsideris/popularconvention) - analyzing code convention from github commits for Github data challenge II
* [RedCoolBeans/dockerlint](https://github.com/RedCoolBeans/dockerlint) - Linting tool for Dockerfiles
* [yujinakayama/atom-lint](https://github.com/yujinakayama/atom-lint) - Obsolete: Generic code linting support for Atom *(archived)*
* [Sumolari/swift-relationship-graph](https://github.com/Sumolari/swift-relationship-graph) - A simple tool to create relationships graphs for Swift codebases
* [jgable/grunt-lesslint](https://github.com/jgable/grunt-lesslint) - Lint LESS files with Grunt
* [marviq/coffee-jshint](https://github.com/marviq/coffee-jshint) - Runs your CoffeeScript source through JSHint to check for errors.
* [helixbass/prettier-plugin-coffeescript](https://github.com/helixbass/prettier-plugin-coffeescript) - Prettier Coffeescript Plugin
* [AtomLinter/linter-coffeelint](https://github.com/AtomLinter/linter-coffeelint) - Linter plugin for CoffeeScript, using coffeelint. *(archived)*
* [za-creature/coffeescope](https://github.com/za-creature/coffeescope) - Scope linter for coffeescript
* [helixbass/eslint-plugin-coffee](https://github.com/helixbass/eslint-plugin-coffee) - ESLint rules for linting Coffeescript source files
* [laurentpayot/floweret](https://github.com/laurentpayot/floweret) - Runtime type annotations for CoffeeScript (and JavaScript too!) *(archived)*
* [coffeelint/coffeelint](https://github.com/coffeelint/coffeelint) - Lint your CoffeeScript.
* [php-integrator/atom-linter-legacy-php56](https://github.com/php-integrator/atom-linter-legacy-php56) - Atom package that lints your PHP source code to indicate various problems such as missing methods. (Legacy) *(archived)*

### Debugging and Profiling

* [AriaMinaei/pretty-error](https://github.com/AriaMinaei/pretty-error) - See node.js errors with less clutter
* [mattinsler/longjohn](https://github.com/mattinsler/longjohn) - Long stack traces for node.js inspired by https://github.com/tlrobinson/long-stack-traces
* [kiddkai/atom-node-debugger](https://github.com/kiddkai/atom-node-debugger) - A Nodejs Debugger For Atom *(archived)*
* [ConradIrwin/async-profile](https://github.com/ConradIrwin/async-profile) - Asynchronous CPU profiling for node
* [electron/mini-breakpad-server](https://github.com/electron/mini-breakpad-server) - Minimum breakpad crash reports collecting server *(archived)*
* [bayleedev/pry.js](https://github.com/bayleedev/pry.js) - :microscope: A REPL for Node.
* [zalmoxisus/atom-redux-devtools](https://github.com/zalmoxisus/atom-redux-devtools) - Redux DevTools Atom package
* [alecperkins/coffeetable](https://github.com/alecperkins/coffeetable) - A drop-in workbench for experimentation, CoffeeTable is a CoffeeScript-fluent browser console.
* [aciidgh/atom-swift-debugger](https://github.com/aciidgh/atom-swift-debugger)
* [acrisci/simple-breakpad-server](https://github.com/acrisci/simple-breakpad-server) - Simple breakpad crash reports collecting server
* [showell/CoffeeScriptLineMatcher](https://github.com/showell/CoffeeScriptLineMatcher) - provides debugging support for CoffeeScript by matching JS lines to CS lines
* [auiWorks/amCoffee](https://github.com/auiWorks/amCoffee) - A CoffeeScript version of the Chrome Console.
* [barc/express-error](https://github.com/barc/express-error) - Error handler which displays source code in error stack for JavaScript and CoffeeScript.

### Editor and IDE Support

* [JoelBesada/activate-power-mode](https://github.com/JoelBesada/activate-power-mode) - Atom package - Activate POWER MODE to write your code in style.
* [atom/vim-mode](https://github.com/atom/vim-mode) - Next generation vim support for atom *(archived)*
* [Glavin001/atom-beautify](https://github.com/Glavin001/atom-beautify) - :mega: Help Wanted - Looking for Maintainer: https://github.com/Glavin001/atom-beautify/issues/2572 | :lipstick: Universal beautification package for Atom editor (:warning: Currently migrating to https://github.com/Unibeautify/ and have very limited bandwidth for Atom-Beautify Issues. Thank you for your patience and understanding :heart: )
* [t9md/atom-vim-mode-plus](https://github.com/t9md/atom-vim-mode-plus) - vim-mode improved
* [chinakids/atom-simplified-chinese-menu](https://github.com/chinakids/atom-simplified-chinese-menu) - Atom 的简体中文汉化扩展,目前最全的汉化包。包含菜单汉化、右键菜单汉化以及设置汉化
* [emmetio/emmet-atom](https://github.com/emmetio/emmet-atom) - Emmet support for Atom *(archived)*
* [atom/tree-view](https://github.com/atom/tree-view) - 🌳 Explore and open project files in Atom *(archived)*
* [jasongilman/proto-repl](https://github.com/jasongilman/proto-repl) - A Clojure Development Environment package for the Atom editor *(archived)*
* [carlosdcastillo/vim-mode](https://github.com/carlosdcastillo/vim-mode) - Experimental next generation vim support for atom. This project needs a new home! *(archived)*
* [atom/highlights](https://github.com/atom/highlights) - Syntax highlighter *(archived)*
* [abe33/atom-pigments](https://github.com/abe33/atom-pigments) - An Atom package to display colors in project and files.
* [jeremyramin/terminal-plus](https://github.com/jeremyramin/terminal-plus) - A terminal package for Atom, complete with themes and more.
* [orktes/atom-react](https://github.com/orktes/atom-react) - ReactJS Support for atom (syntax, snippets)
* [gandm/language-babel](https://github.com/gandm/language-babel) - ES2017, flow, React JSX and GraphQL grammar and transpilation for ATOM
* [SublimeText/CoffeeScript](https://github.com/SublimeText/CoffeeScript) - Syntax highlighting and checking, commands, shortcuts, snippets, watched compilation and more.
* [blakeembrey/atom-dash](https://github.com/blakeembrey/atom-dash) - Dash documentation integration with Atom
* [caiogondim/js-patterns-sublime-snippets](https://github.com/caiogondim/js-patterns-sublime-snippets) - :mortar_board: JavaScript Patterns snippets for Sublime Text
* [zhuochun/md-writer](https://github.com/zhuochun/md-writer) - ✒️ Make Atom a better Markdown/AsciiDoc editor for writers and bloggers *(archived)*
* [alibaba/Thera](https://github.com/alibaba/Thera) - Thera is an integrated development environment(IDE) powered by Alibaba.com aimed for improving mobile hybrid solution develop experience, such as weex, luaview, react native.
* [f/atom-term2](https://github.com/f/atom-term2) - THIS PROJECT IS NO LONGER MAINTAINED. PLEASE USE ATOM TERM3 PACKAGE
* [angular-ui/AngularJS-Atom](https://github.com/angular-ui/AngularJS-Atom) - An AngularJS package for Github's Atom editor *(archived)*
* [lsegal/atom-runner](https://github.com/lsegal/atom-runner) - This package will run various script files inside of Atom. It currently supports JavaScript, CoffeeScript, Ruby, and Python. You can add more. *(archived)*
* [atom/settings-view](https://github.com/atom/settings-view) - 🔧 Edit Atom settings *(archived)*
* [thiagopnts/unregistered](https://github.com/thiagopnts/unregistered) - :registered: Best Atom plugin for sublime text users
* [coolwanglu/neovim-e](https://github.com/coolwanglu/neovim-e) - Electron UI for Neovim
* [Gert-dev/php-ide-serenata](https://github.com/Gert-dev/php-ide-serenata) - Atom IDE package that integrates the Serenata server to provide PHP code assistance
* [klorenz/atom-regex-railroad-diagrams](https://github.com/klorenz/atom-regex-railroad-diagrams) - display regex as railroad diagram, if cursor moves to it
* [autocomplete-python/autocomplete-python](https://github.com/autocomplete-python/autocomplete-python) - Jedi based Python autocomplete for Atom
* [thomaslindstrom/color-picker](https://github.com/thomaslindstrom/color-picker) - A color picker for the Atom Editor. Right click a color and select color picker to open it.
* [yongkangchen/remote-sync](https://github.com/yongkangchen/remote-sync) - Upload your files to remote host after every change. Both SCP/SFTP and FTP are supported.
* [bigfive/atom-sublime-select](https://github.com/bigfive/atom-sublime-select) - Enable 'sublime style' multiline selection boxes to Atom editor http://atom.io
* [atom-archive/terminal](https://github.com/atom-archive/terminal) - Atom Terminal package - *not currently maintained* *(archived)*
* [avendael/atomic-emacs](https://github.com/avendael/atomic-emacs) - An atomic implementation of emacs keybindings for the Atom text editor.
* [robinsloan/rnn-writer](https://github.com/robinsloan/rnn-writer) - Package for the Atom text editor that provides responsive, inline "autocomplete" powered by a recurrent neural network.
* [JunoLab/uber-juno](https://github.com/JunoLab/uber-juno) - Installer package for the Juno IDE
* [atom/language-javascript](https://github.com/atom/language-javascript) - JavaScript language package for Atom *(archived)*
* [defunkt/Zen](https://github.com/defunkt/Zen) - Distraction free writing for Atom.
* [atom/language-python](https://github.com/atom/language-python) - Python package for Atom *(archived)*
* [mrodalgaard/atom-todo-show](https://github.com/mrodalgaard/atom-todo-show) - Atom package that shows a list of todos from your project.
* [cocoakekeyu/markdown-img-paste](https://github.com/cocoakekeyu/markdown-img-paste) - 一个可以快速粘贴剪贴板里的照片到markdown的插件，并且可以设置使用七牛存储照片。
* [elixir-editors/language-elixir](https://github.com/elixir-editors/language-elixir) - Elixir language support for the Atom editor.
* [harmsk/atom-html-preview](https://github.com/harmsk/atom-html-preview) - Atom HTML Live Preview Package *(archived)*
* [lloeki/ex-mode](https://github.com/lloeki/ex-mode) - Ex mode for Atom
* [abe33/atom-tablr](https://github.com/abe33/atom-tablr) - Edit CSV files using a table editor
* [irrationalistic/atom-tasks](https://github.com/irrationalistic/atom-tasks) - Handle tasks/todo files in atom
* [sveale/remote-edit](https://github.com/sveale/remote-edit) - remote-edit
* [asciidoctor/atom-asciidoc-preview](https://github.com/asciidoctor/atom-asciidoc-preview) - ⚛ AsciiDoc preview for the Atom editor. *(archived)*
* [Peekmo/atom-autocomplete-php](https://github.com/Peekmo/atom-autocomplete-php) - Autocomplete for PHP in atom editor *(archived)*
* [jcouyang/glist](https://github.com/jcouyang/glist) - Taking notes with :octocat: Gist from Atom
* [andischerer/atom-keyboard-localization](https://github.com/andischerer/atom-keyboard-localization) - [DEPRECATED] Keyboard localization package for non US-Keyboard Layouts
* [atom/language-php](https://github.com/atom/language-php) - PHP package for Atom *(archived)*
* [Chris911/Ask-Stack-Atom](https://github.com/Chris911/Ask-Stack-Atom) - Ask Stack Overflow for Atom
* [atom/language-c](https://github.com/atom/language-c) - C support in Atom *(archived)*
* [DavidLGoldberg/jumpy](https://github.com/DavidLGoldberg/jumpy) - The fastest way to jump around files and across visible panes in Atom
* [dundalek/atom-markdown-mindmap](https://github.com/dundalek/atom-markdown-mindmap) - Visualize markdown files as mindmaps in Atom editor
* [atom/tabs](https://github.com/atom/tabs) - Tabs in Atom *(archived)*
* [wavded/gedit-coffeescript](https://github.com/wavded/gedit-coffeescript) - gedit Syntax Highlighting for CoffeeScript files
* [xndcn/symbols-tree-view](https://github.com/xndcn/symbols-tree-view) - A symbols view like taglist for Atom.io
* [zargony/atom-language-rust](https://github.com/zargony/atom-language-rust) - Rust language support in Atom - LOOKING FOR MAINTAINER, see #144 *(archived)*
* [edubkendo/atom-racer](https://github.com/edubkendo/atom-racer) - Intelligent code completion for Rust in the Atom Editor. Requires Racer.
* [atom/language-html](https://github.com/atom/language-html) - HTML package for Atom *(archived)*
* [MattFlower/organized](https://github.com/MattFlower/organized) - Outlining, scheduling, and todos inside of the Atom Editor
* [yasuyuky/autocomplete-clang](https://github.com/yasuyuky/autocomplete-clang) - *(archived)*
* [atom/language-go](https://github.com/atom/language-go) - Go language package for Atom *(archived)*
* [atom/atom-keymap](https://github.com/atom/atom-keymap) - Atom's selector-based keymap system *(archived)*
* [skandasoft/browser-plus](https://github.com/skandasoft/browser-plus) - Browser For Atom
* [AtomLinter/linter-write-good](https://github.com/AtomLinter/linter-write-good) - An Atom linter interface for write-good. *(archived)*
* [atom/language-gfm](https://github.com/atom/language-gfm) - GitHub Flavored Markdown in Atom *(archived)*
* [atom/status-bar](https://github.com/atom/status-bar) - Status bar for Atom *(archived)*
* [mattberkowitz/autoclose-html](https://github.com/mattberkowitz/autoclose-html) - Autoclose html tags in atom
* [extrabacon/atom-turbo-javascript](https://github.com/extrabacon/atom-turbo-javascript) - Commands and snippets for faster Javascript and Typescript with the Atom Editor
* [fankserver/atom-firepad](https://github.com/fankserver/atom-firepad) - Collaborative code editing with Atom + Firepad
* [styczynski/atom-terminal-panel](https://github.com/styczynski/atom-terminal-panel) - Advanced terminal interface for Atom editor
* [vincentcn/markdown-scroll-sync](https://github.com/vincentcn/markdown-scroll-sync) - Auto-scroll markdown-preview tab to match markdown source
* [danhper/atomic-chrome-atom](https://github.com/danhper/atomic-chrome-atom) - Edit Chrome textareas in Atom
* [aki77/atom-expand-region](https://github.com/aki77/atom-expand-region) - expanding selection *(archived)*
* [crucialfelix/atom-supercollider](https://github.com/crucialfelix/atom-supercollider) - SuperCollider development environment for Atom.io
* [lukehoban/atom-ide-flow](https://github.com/lukehoban/atom-ide-flow) - Atom IDE support for Flow
* [raccy/japanese-wrap](https://github.com/raccy/japanese-wrap) - Atom package extend word wrap for Japanese text.
* [bus-stop/Termination](https://github.com/bus-stop/Termination) - Integrated terminal for Atom. Looks like terminal-plus, acts like your native terminal (except every other Friday). Looking for collaborators! :-)
* [EtienneLem/atom-rdio](https://github.com/EtienneLem/atom-rdio) - Adds Rdio controls to Atom and displays the currently playing song in the status bar *(archived)*
* [randy3k/remote-atom](https://github.com/randy3k/remote-atom) - rmate for atom
* [Qusic/atom-youcompleteme](https://github.com/Qusic/atom-youcompleteme) - YouCompleteMe for Atom Editor *(archived)*
* [atom/language-todo](https://github.com/atom/language-todo) - TODO highlighting package for Atom *(archived)*
* [joshwcomeau/nice-index](https://github.com/joshwcomeau/nice-index) - Atom package to rename `index.js` files to their parent directory names
* [f/atom-bootstrap3](https://github.com/f/atom-bootstrap3) - Twitter Bootstrap 3 Snippets for Atom
* [abe33/atom-bezier-curve-editor](https://github.com/abe33/atom-bezier-curve-editor)
* [abe33/atom-color-highlight](https://github.com/abe33/atom-color-highlight) - Highlights color declarations in files
* [atom/autocomplete-emojis](https://github.com/atom/autocomplete-emojis) - autocomplete+ emoji autocompletion *(archived)*
* [seongjaelee/nvatom](https://github.com/seongjaelee/nvatom) - nvatom (unpublished from atom.io)
* [atom/notifications](https://github.com/atom/notifications) - User notifications *(archived)*
* [atom-haskell/language-haskell](https://github.com/atom-haskell/language-haskell) - Haskell language support for Atom *(archived)*
* [mpeterson2/save-session](https://github.com/mpeterson2/save-session) - An Atom package to restore your session.
* [sanusart/atom-wrap-in-tag](https://github.com/sanusart/atom-wrap-in-tag) - Simplest package for Atom editor that wraps HTML tag around selection
* [satococoa/atom-rubymotion](https://github.com/satococoa/atom-rubymotion) - RubyMotion support in Atom
* [atom/autocomplete-css](https://github.com/atom/autocomplete-css) - CSS property name and value completions *(archived)*
* [kepta/atom-css-to-inline](https://github.com/kepta/atom-css-to-inline) - Atom plugin for converting css to inline for react/JSX
* [sjlevine/atom-slime](https://github.com/sjlevine/atom-slime) - Write lisp code efficiently with Atom
* [mantrajs/mantrajs-atom-package](https://github.com/mantrajs/mantrajs-atom-package) - Mantra JS - Package for Atom
* [atom/language-java](https://github.com/atom/language-java) - Java package for Atom *(archived)*
* [edubkendo/atom-elm](https://github.com/edubkendo/atom-elm) - An atom package providing syntax highlighting and snippets for the Elm language.
* [guileen/terminal-status](https://github.com/guileen/terminal-status) - Atom terminal status
* [misfo/jim](https://github.com/misfo/jim) - Vim mode for Ace (Github & Cloud9's editor)
* [neil-lindquist/SLIMA](https://github.com/neil-lindquist/SLIMA) - Superior Lisp Interactive Mode for Pulsar
* [atom-archive/autocomplete](https://github.com/atom-archive/autocomplete) - See https://github.com/atom/autocomplete-plus for the package currently bundled with Atom *(archived)*
* [atom/atom-space-pen-views](https://github.com/atom/atom-space-pen-views) - Atom SpacePen views that previously lived in core. *(archived)*
* [ioquatix/script-runner](https://github.com/ioquatix/script-runner) - This package will run various script files inside of Atom. It currently supports JavaScript, CoffeeScript, Ruby, and Python. You can add more. *(archived)*
* [atom/language-coffee-script](https://github.com/atom/language-coffee-script) - CoffeeScript support in Atom *(archived)*
* [caiogondim/js-console-sublime-snippets](https://github.com/caiogondim/js-console-sublime-snippets) - :computer: JavaScript and CoffeeScript Console snippets
* [execjosh/atom-file-types](https://github.com/execjosh/atom-file-types) - Specify additional file types for languages. *(archived)*
* [ianhattendorf/autocomplete-ruby](https://github.com/ianhattendorf/autocomplete-ruby) - Provides intelligent code completion for Ruby in the Atom editor. Requires RSense.
* [mtscout6/vim-cjsx](https://github.com/mtscout6/vim-cjsx) - Vim plugins for CJSX files (CoffeeScript with React JSX)
* [tanepiper/cloud9-livecoffee-ext](https://github.com/tanepiper/cloud9-livecoffee-ext) - A extension for Cloud9ide for CoffeeScript functionality *(archived)*
* [nfiniteset/CoffeeScript.mode](https://github.com/nfiniteset/CoffeeScript.mode) - A CoffeeScript syntax coloring mode for Coda and SubEthaEdit
* [alohaas/language-nunjucks](https://github.com/alohaas/language-nunjucks) - Syntax highlighting for nunjucks templates in atom.
* [wende/autocomplete-elixir](https://github.com/wende/autocomplete-elixir) - Intelligent Elixir autocompletion provider for Atom autocomplete-plus *(archived)*
* [smashwilson/stacktrace](https://github.com/smashwilson/stacktrace) - Atom package to navigate stacktraces.
* [robhurring/atom-change-case](https://github.com/robhurring/atom-change-case) - atom plugin for node-change-case
* [php-integrator/atom-autocompletion](https://github.com/php-integrator/atom-autocompletion) - Atom package that provides autocompletion for your PHP source code. *(archived)*
* [cdnjs/atom-extension](https://github.com/cdnjs/atom-extension) - ⚛ Atom extension for easily inserting scripts *(archived)*
* [pfefferle/atom-php-cs-fixer](https://github.com/pfefferle/atom-php-cs-fixer) - Run the 'PHP Coding Standards Fixer' within Atom *(archived)*
* [yeungda/coffeescript-idea](https://github.com/yeungda/coffeescript-idea) - ABANDONED CoffeeScript Plugin for IntelliJ IDEA
* [php-integrator/atom-navigation](https://github.com/php-integrator/atom-navigation) - Atom package that provides code navigation and go to functionality for your PHP source code. *(archived)*
* [gmendonca/px-to-rem](https://github.com/gmendonca/px-to-rem) - Atom package to convert pixels to rem
* [miketheman/language-diff](https://github.com/miketheman/language-diff) - ARCHIVED - Atom editor itself is archived *(archived)*
* [bh/atom-python-isort](https://github.com/bh/atom-python-isort) - Atom.io plugin to sort Python imports *(archived)*

### Version Control

* [littlebee/git-time-machine](https://github.com/littlebee/git-time-machine) - Atom package that allows you to travel back in commit history
* [akonwi/git-plus](https://github.com/akonwi/git-plus) - vim-fugitive like package for atom. make commits and other git things without the terminal *(archived)*
* [smashwilson/merge-conflicts](https://github.com/smashwilson/merge-conflicts) - Resolve git merge conflicts in Atom *(archived)*
* [zmoazeni/gitspective](https://github.com/zmoazeni/gitspective) - A different github timeline
* [jacogr/atom-git-control](https://github.com/jacogr/atom-git-control) - Not maintained :( *(archived)*
* [diiq/atomatigit](https://github.com/diiq/atomatigit) - Atom-ati-Git. Git intergration for Atom.io, in the style of Magit. UNMAINTAINED. SEEKING NEW MAINTAINER. *(archived)*
* [pazdera/gitwalk](https://github.com/pazdera/gitwalk) - Bulk processing of git repositories
* [dogweather/repo-health-check](https://github.com/dogweather/repo-health-check) - Analyze a project: How are the maintainers doing?
* [jung-kim/atom-ungit](https://github.com/jung-kim/atom-ungit) - Atom plugin for Ungit project
* [wollzelle/gitlab-github-migrate](https://github.com/wollzelle/gitlab-github-migrate) - Migrate repositories, wikis, issues and milestones from GitLab to GitHub *(archived)*

## Web

### Web Frameworks

* [jnordberg/wintersmith](https://github.com/jnordberg/wintersmith) - A flexible static site generator
* [docpad/docpad](https://github.com/docpad/docpad) - Empower your website frontends with layouts, meta-data, pre-processors (markdown, jade, coffeescript, etc.), partials, skeletons, file watching, querying, and an amazing plugin system. DocPad will streamline your web development process allowing you to craft powerful static sites quicker than ever before.
* [chaplinjs/chaplin](https://github.com/chaplinjs/chaplin) - HTML5 application architecture using Backbone.js *(archived)*
* [mauricemach/zappa](https://github.com/mauricemach/zappa) - Node development for the lazy.
* [techpines/bone.io](https://github.com/techpines/bone.io) - Realtime HTML5 Framework
* [varvet/serenade.js](https://github.com/varvet/serenade.js) - Client side MVC framework *(archived)*
* [maccman/ace](https://github.com/maccman/ace) - Sinatra for Node
* [jashkenas/journo](https://github.com/jashkenas/journo) - A quick-and-dirty (literate) blogging engine
* [flosse/scaleApp](https://github.com/flosse/scaleApp) - scaleApp is a JavaScript framework for scalable and maintainable One-Page-Applications *(archived)*
* [joosy/joosy](https://github.com/joosy/joosy) - Joosy is a browser applications framework. That is based on Rails, CoffeeScript and love.
* [lega911/angular-light](https://github.com/lega911/angular-light) - Alight is a library for building interactive MVVM web interfaces/applications. (project is deprecated)
* [mizchi/arda](https://github.com/mizchi/arda) - Meta-Flux Framework
* [noflo/noflo-jekyll](https://github.com/noflo/noflo-jekyll) - Flow-based reimplementation of the Jekyll static site generator *(archived)*
* [fahad19/singool](https://github.com/fahad19/singool) - Backbone.js based framework for developing single-page web applications
* [jclevy/chocolatejs](https://github.com/jclevy/chocolatejs) - Chocolate - Full stack and isomorphic Node.js web framework and online ide
* [invisiblejs/invisible](https://github.com/invisiblejs/invisible) - Invisible.js: Reusable models for the client and the server
* [efacilitation/eventric](https://github.com/efacilitation/eventric) - Minimalist JavaScript framework to build applications based on DDD, CQRS and Event Sourcing.
* [meteor-activeroute/legacy](https://github.com/meteor-activeroute/legacy) - Active route helpers for the most popular routers in Meteor
* [svasva/meteor-publish-with-relations](https://github.com/svasva/meteor-publish-with-relations) - Meteor.js SmartPackage to publish associated collections at once.
* [Meteor-Community-Packages/meteor-partitioner](https://github.com/Meteor-Community-Packages/meteor-partitioner) - Transparently divide a single meteor app into several different instances shared between different groups of users.
* [davidedc/Fizzygum](https://github.com/davidedc/Fizzygum) - a new web framework, an entire platform really, designed from the ground up to handle complex things easily. Put the power of an entire Operating System at your fingertips.
* [peerlibrary/meteor-reactive-publish](https://github.com/peerlibrary/meteor-reactive-publish) - Reactive publish endpoints
* [arillo/meteor-flow-router-helpers](https://github.com/arillo/meteor-flow-router-helpers) - Template helpers for meteorhacks:flow-router, pathFor, subsReady, urlFor, queryParam
* [rthauby/Paige](https://github.com/rthauby/Paige) - Super simple project page generation
* [dgladkov/django-turbolinks](https://github.com/dgladkov/django-turbolinks) - Drop-in turbolinks implementation for Django
* [ahmednuaman/radian](https://github.com/ahmednuaman/radian) - A scalable AngularJS framework
* [soyjavi/monocle](https://github.com/soyjavi/monocle) - Build Awesome CoffeeScript MVC Applications
* [carrot/roots-contentful](https://github.com/carrot/roots-contentful) - A roots extension to work with data from Contentful's API. https://www.contentful.com/
* [fortes/enfield](https://github.com/fortes/enfield) - [Not Maintained!] Jekyll-like static site generator for node.js *(archived)*
* [meteor-space/base](https://github.com/meteor-space/base) - Foundation for Modular Application Architecture in Meteor.
* [donpark/session-mongoose](https://github.com/donpark/session-mongoose) - `connect` Mongoose session store *(archived)*
* [cozy/americano](https://github.com/cozy/americano) - Deprecated - Make Express.js more opinioniated about configuration *(archived)*
* [Zorium/zorium](https://github.com/Zorium/zorium) - (╯°□°)╯︵ ┻━┻ The CoffeeScript Web Framework
* [adaltas/node-connect-coffee-script](https://github.com/adaltas/node-connect-coffee-script) - Connect middleware to serve CoffeeScript files
* [stanfeldman/wheels](https://github.com/stanfeldman/wheels) - Node.js web framework written in CoffeeScript. Simple and sexy.
* [gothamjs/framework](https://github.com/gothamjs/framework) - Coffeescript Framework for front-end development
* [fntz/sirius](https://github.com/fntz/sirius) - Modern coffeescript/javascript framework
* [mattinsler/caboose](https://github.com/mattinsler/caboose) - Coffeescript-happy express-based server-side MVC framework loosely based on rails
* [jysperm/Cichorium](https://github.com/jysperm/Cichorium) - Routing framework based on Promise using CoffeeScript

### HTTP and Networking Clients

* [pksunkara/octonode](https://github.com/pksunkara/octonode) - github api v3 in nodejs *(archived)*
* [jpillora/jquery.rest](https://github.com/jpillora/jquery.rest) - A jQuery plugin for easy consumption of RESTful APIs
* [Nedomas/databound](https://github.com/Nedomas/databound) - Provides Javascript a simple API to the Ruby on Rails CRUD.
* [t3chnoboy/amazon-product-api](https://github.com/t3chnoboy/amazon-product-api) - :credit_card: Amazon Product Advertising API client
* [mckelvey/instagram-node-lib](https://github.com/mckelvey/instagram-node-lib) - The Instagram Node Lib is a helper library for node that makes communicating with the Instagram API easy.
* [pandastrike/shred](https://github.com/pandastrike/shred) - A Node.js HTTP Client
* [goodeggs/angular-cached-resource](https://github.com/goodeggs/angular-cached-resource) - An AngularJS module to interact with RESTful resources, even when browser is offline
* [KyleAMathews/superagent-bluebird-promise](https://github.com/KyleAMathews/superagent-bluebird-promise) - Add promise support to superagent using Bluebird
* [davidchambers/tutor](https://github.com/davidchambers/tutor) - JavaScript interface for the Gatherer card database
* [cozy/request-json](https://github.com/cozy/request-json) - Http Client to deal easily with JSON API *(archived)*
* [christiansmith/ngGAPI](https://github.com/christiansmith/ngGAPI) - AngularJS Google API Client
* [pwnall/node-xhr2](https://github.com/pwnall/node-xhr2) - XMLHttpRequest emulator for node.js
* [nkohari/node-hipchat](https://github.com/nkohari/node-hipchat) - simple node.js library for communicating with hipchat's rest api
* [technoweenie/node-scoped-http-client](https://github.com/technoweenie/node-scoped-http-client) - Unmaintained. Free push/npm access to anyone interested.
* [oozcitak/akismet-js](https://github.com/oozcitak/akismet-js) - Akismet API client for node.js
* [CedX/Akismet.js](https://github.com/CedX/Akismet.js) - Prevent comment spam using Akismet service, in JavaScript.

### API and GraphQL

* [danielgtaylor/aglio](https://github.com/danielgtaylor/aglio) - An API Blueprint renderer with theme support that outputs static HTML
* [kahmali/meteor-restivus](https://github.com/kahmali/meteor-restivus) - REST APIs for the Best of Us! - A Meteor 0.9+ package for building REST APIs https://atmospherejs.com/nimble/restivus
* [rockets/rockets](https://github.com/rockets/rockets) - Streams new posts and comments as they are created on reddit.com
* [apiaxle/apiaxle](https://github.com/apiaxle/apiaxle) - The apiaxle project
* [Electroid/mojang-api](https://github.com/Electroid/mojang-api) - Bundle multiple Minecraft APIs into a single GET request.
* [mbertolacci/lorem-rss](https://github.com/mbertolacci/lorem-rss) - Code for a webservice that generates Lorem Ipsum RSS at specified intervals, available at http://lorem-rss.herokuapp.com
* [intellinote/swagger-dsl](https://github.com/intellinote/swagger-dsl) - A CoffeeScript-based domain-specific language for generating JSON documents for Swagger.
* [mikekelly/backbone.hal](https://github.com/mikekelly/backbone.hal) - Hypermedia for Backbone.js
* [filearts/plunker_api](https://github.com/filearts/plunker_api) - The public API off of which Plunker runs *(archived)*
* [zooniverse/scribeAPI](https://github.com/zooniverse/scribeAPI) - scribe API *(archived)*
* [Boxyco/hackernews-api](https://github.com/Boxyco/hackernews-api) - A RESTful API for news.ycombinator.com written in Coffeescript for node.js

### Frontend and UI Components

* [basecamp/trix](https://github.com/basecamp/trix) - A rich text editor for everyday writing
* [mojs/mojs](https://github.com/mojs/mojs) - The motion graphics toolbelt for the web
* [dropzone/dropzone](https://github.com/dropzone/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars.
* [michaelvillar/dynamics.js](https://github.com/michaelvillar/dynamics.js) - Javascript library to create physics-based animations
* [ichord/At.js](https://github.com/ichord/At.js) - Add Github like mentions autocomplete to your application.
* [sorich87/bootstrap-tour](https://github.com/sorich87/bootstrap-tour) - Quick and easy product tours with Twitter Bootstrap Popovers
* [turbolinks/turbolinks-classic](https://github.com/turbolinks/turbolinks-classic) - Classic version of Turbolinks. Now deprecated in favor of Turbolinks 5. *(archived)*
* [stevenschobert/instafeed.js](https://github.com/stevenschobert/instafeed.js) - A simple Instagram JavaScript plugin for your website
* [dmauro/Keypress](https://github.com/dmauro/Keypress) - A keyboard input capturing utility in which any key can be a modifier key.
* [leafo/sticky-kit](https://github.com/leafo/sticky-kit) - A jQuery plugin for creating smart sticky elements
* [gss/engine](https://github.com/gss/engine) - GSS engine
* [angular-ui/angular-google-maps](https://github.com/angular-ui/angular-google-maps) - AngularJS directives for the Google Maps Javascript API *(archived)*
* [bergie/hallo](https://github.com/bergie/hallo) - Simple rich text editor (contentEditable) for jQuery UI *(archived)*
* [dmotz/oriDomi](https://github.com/dmotz/oriDomi) - 🪭 Fold up DOM elements like paper
* [soyjavi/QuoJS](https://github.com/soyjavi/QuoJS) - Micro #JavaScript Library for Mobile Devices
* [serkanyersen/ifvisible.js](https://github.com/serkanyersen/ifvisible.js) - Crossbrowser & lightweight way to check if user is looking at the page or interacting with it.
* [nathansearles/slidesjs](https://github.com/nathansearles/slidesjs) - SlidesJS is obsolete and no longer maintained. *(archived)*
* [AshesOfOwls/jquery.shapeshift](https://github.com/AshesOfOwls/jquery.shapeshift) - A dynamic grid system with drag and drop functionality.
* [Pathgather/please-wait](https://github.com/Pathgather/please-wait) - A simple library to show your users a beautiful splash page while your application loads.
* [easelinc/tourist](https://github.com/easelinc/tourist) - Simple, flexible tours for your app *(archived)*
* [passy/angular-masonry](https://github.com/passy/angular-masonry) - An AngularJS directive for Masonry. *(archived)*
* [kossnocorp/jquery.turbolinks](https://github.com/kossnocorp/jquery.turbolinks) - 💀 Deprecated ⚠️ jQuery plugin for drop-in fix binded events problem caused by Turbolinks *(archived)*
* [ksylvest/jquery-gridly](https://github.com/ksylvest/jquery-gridly) - Gridly is a jQuery plugin to enable dragging and dropping as well as resizing on a grid.
* [fredwu/jquery-endless-scroll](https://github.com/fredwu/jquery-endless-scroll) - Endless/infinite scrolling/pagination.
* [yogiben/meteor-admin](https://github.com/yogiben/meteor-admin) - A complete admin dashboard solution
* [gterrono/houston](https://github.com/gterrono/houston) - A zero-config, Django Admin-like admin for Meteor
* [alekseykulikov/backbone-offline](https://github.com/alekseykulikov/backbone-offline) - [Deprecated] Allows your Backbone.js app to work offline
* [nickperkinslondon/angular-bootstrap-nav-tree](https://github.com/nickperkinslondon/angular-bootstrap-nav-tree) - An AngularJS directive that creates a Tree based on a Bootstrap "nav" list.
* [replit-archive/jq-console](https://github.com/replit-archive/jq-console) - Feature complete web terminal
* [kelp404/angular-form-builder](https://github.com/kelp404/angular-form-builder) - Drag and drop to build bootstrap forms in AngularJS.
* [atom-archive/space-pen](https://github.com/atom-archive/space-pen) - A simple and powerful client-side view framework that works in zero-gravity, no longer maintained. *(archived)*
* [jessepollak/payment](https://github.com/jessepollak/payment) - :moneybag: A jQuery-free general purpose library for building credit card forms, validating inputs and formatting numbers.
* [huacnlee/social-share-button](https://github.com/huacnlee/social-share-button) - Helper for add social share feature in your Rails app. Twitter, Facebook, Weibo, Douban ...
* [d4nyll/lethargy](https://github.com/d4nyll/lethargy) - Distinguish between scroll events initiated by the user, and those by inertial scrolling
* [HubSpot/signet](https://github.com/HubSpot/signet) - Display a unique seal in the developer console of your page
* [tdreyno/iphone-style-checkboxes](https://github.com/tdreyno/iphone-style-checkboxes) - Turn your checkboxes into iOS-style binary switches *(archived)*
* [maxwells/bootstrap-tags](https://github.com/maxwells/bootstrap-tags) - Bootstrap-themed jquery tag interface
* [fragaria/angular-daterangepicker](https://github.com/fragaria/angular-daterangepicker) - Angular.js wrapper for dangrossman/bootstrap-daterangepicker
* [yesmeck/jquery-jsonview](https://github.com/yesmeck/jquery-jsonview) - [UNMAINTAINED]View JSON in a more readable format *(archived)*
* [fulmicoton/fattable](https://github.com/fulmicoton/fattable) - Javascript Library to create scrollable table with infinite rows and columns.
* [layerssss/paste.js](https://github.com/layerssss/paste.js) - read image/text data from clipboard (cross-browser)
* [harvesthq/harvey](https://github.com/harvesthq/harvey) - Adding a second face to your application's JavaScript *(archived)*
* [awt2542/ViewController-for-Framer](https://github.com/awt2542/ViewController-for-Framer) - Multi step user flows in Framer.js
* [meltingice/ajax-chosen](https://github.com/meltingice/ajax-chosen) - A complement to the jQuery library Chosen that adds ajax autocomplete
* [alethes/meteor-pages](https://github.com/alethes/meteor-pages) - Meteor pagination
* [binnng/slip.js](https://github.com/binnng/slip.js) - 移动端跟随手指滑动组件，零依赖。
* [adamalbrecht/ngQuickDate](https://github.com/adamalbrecht/ngQuickDate) - An Angular.js Date/Time picker directive that stresses speed of data entry and configuration
* [dannvix/ColorTunes](https://github.com/dannvix/ColorTunes) - HTML5 version of the iTunes 11 album view
* [peerlibrary/meteor-blaze-components](https://github.com/peerlibrary/meteor-blaze-components) - Reusable components for Blaze
* [Meteor-Community-Packages/meteor-autocomplete](https://github.com/Meteor-Community-Packages/meteor-autocomplete) - Client/server autocompletion designed for Meteor's collections and reactivity.
* [ajimix/Input-Framer](https://github.com/ajimix/Input-Framer) - Framer module to add inputs to your prototypes and easily turn your designs inputs into real inputs
* [matiasgali/guillotine](https://github.com/matiasgali/guillotine) - jQuery plugin to crop images within an area (fully responsive), allowing to drag (touch support), zoom and rotate.
* [unamohq/Typist](https://github.com/unamohq/Typist) - Elegant automated typing, for your text rotation needs
* [sensortower/daterangepicker](https://github.com/sensortower/daterangepicker) - Date range picker component for the modern web *(archived)*
* [wistia/fresh-url](https://github.com/wistia/fresh-url) - Drop this script on your page and enjoy the freshest of URLs *(archived)*
* [bobtail-dev/bobtail](https://github.com/bobtail-dev/bobtail) - A lightweight CoffeeScript library/DSL for reactive programming and declaratively building scalable web UIs
* [jawj/OverlappingMarkerSpiderfier-Leaflet](https://github.com/jawj/OverlappingMarkerSpiderfier-Leaflet) - Deals with overlapping markers in the Leaflet maps API, Google Earth-style
* [awt2542/textLayer-for-Framer](https://github.com/awt2542/textLayer-for-Framer) - Framer.js module that simplifies the process of adding text to your prototypes.
* [huacnlee/jquery.qeditor](https://github.com/huacnlee/jquery.qeditor) - This is a simple WYSIWYG editor with jQuery. *(archived)*
* [prajwalkman/angular-slider](https://github.com/prajwalkman/angular-slider) - (DEPRECATED) Slider directive implementation for AngularJS, without jQuery dependencies *(archived)*
* [JohnyDays/react-credit-card](https://github.com/JohnyDays/react-credit-card) - React port of the display part of Card by @jessepollak
* [mreq/slick-lightbox](https://github.com/mreq/slick-lightbox) - A lightbox wrapper for Ken's amazing slick carousel. *(archived)*
* [chriscamargo/framer-viewNavigationController](https://github.com/chriscamargo/framer-viewNavigationController) - A simple controller for FramerJS that allows you to transition between views with just a couple lines of code.
* [hakanersu/AmaranJS](https://github.com/hakanersu/AmaranJS) - Nice, sleek and stylish notifications.
* [paulpflug/vue-mixins](https://github.com/paulpflug/vue-mixins) - A collection of mixins in vue
* [straydogstudio/film_roll](https://github.com/straydogstudio/film_roll) - A lightweight jQuery carousel that centers one item at a time on the page.
* [ManuelDeLeon/viewmodel](https://github.com/ManuelDeLeon/viewmodel) - MVVM for Meteor
* [thenikso/angular-flexslider](https://github.com/thenikso/angular-flexslider) - AngularJS directive to use Woothemes' FlexSlider jQuery plugin.
* [pughpugh/react-countdown-clock](https://github.com/pughpugh/react-countdown-clock) - HTML5 canvas countdown clock React component
* [iamdanfox/typetype](https://github.com/iamdanfox/typetype) - human typing with jQuery
* [microsoft/windows-framer-toolkit](https://github.com/microsoft/windows-framer-toolkit) - Windows 10 UWP framer prototyping toolkit. *(archived)*
* [pongstr/pongstgrm](https://github.com/pongstr/pongstgrm) - jquery plugin that displays your instagram media to your web page *(archived)*
* [akatov/angular-contenteditable](https://github.com/akatov/angular-contenteditable) - angular model for the "contenteditable" attribute *(archived)*
* [florianguenther/zui53](https://github.com/florianguenther/zui53) - ZUI53 is a JavaScript Library to create powerfull webbased Zoomable User Interfaces (ZUIs) with new technologies like HTML5 and CSS3.
* [balena-io/triangular.js](https://github.com/balena-io/triangular.js) - A natural fusion between d3 and angular.js. See http://alexandros.resin.io/angular-d3-svg/ for more information *(archived)*
* [joshpuckett/FramerModules](https://github.com/joshpuckett/FramerModules) - Modules that extend Framer.js
* [johnnyfreeman/revolver](https://github.com/johnnyfreeman/revolver) - A javascript library for building your own content slider. *(archived)*
* [ro31337/jquery.ns-autogrow](https://github.com/ro31337/jquery.ns-autogrow) - Automatically adjust textarea width/height based on user input. Non-sucking version.
* [paulpflug/vue-materialize](https://github.com/paulpflug/vue-materialize) - materialize - done in vue
* [craigspaeth/jquery.fillwidth](https://github.com/craigspaeth/jquery.fillwidth) - Line up images to the edge of their container (like google images) without cropping
* [72/lottie-framer](https://github.com/72/lottie-framer) - A Framer module that uses AirBnb's Lottie-Web to render animations exported from After Effects (JSON files)
* [kelp404/angular-validator](https://github.com/kelp404/angular-validator) - AngularJS form validation.
* [gre/deprecated-flexible-nav](https://github.com/gre/deprecated-flexible-nav) - NOT MAINTAINED – Improve your navigation experience - this jQuery lib improves a webpage navigation and helps to visualize different sections. of a document, an article,.. any web page. *(archived)*
* [jonstipe/number-polyfill](https://github.com/jonstipe/number-polyfill) - A polyfill for implementing the HTML5 <input type="number"> element in browsers that do not currently support it.
* [dmotz/TuringType](https://github.com/dmotz/TuringType) - ⌨️ Simple human typing effect
* [WealthBar/angular-d3](https://github.com/WealthBar/angular-d3) - AngularJS directives for declaratively using D3
* [codecombat/treema](https://github.com/codecombat/treema) - jQuery plugin that generates HTML interfaces to edit JSON data defined by json-schema.
* [adamalbrecht/ngOnboarding](https://github.com/adamalbrecht/ngOnboarding) - A tooltip-tutorial / onboarding framework for Angular.js *(archived)*
* [engelfrost/svg-input-elements](https://github.com/engelfrost/svg-input-elements) - A JavaScript implementation of an SVG textarea. WIP.
* [KyleAMathews/react-sparkline](https://github.com/KyleAMathews/react-sparkline) - React component for rendering simple sparklines
* [bugsnag/chromatic-sass](https://github.com/bugsnag/chromatic-sass) - Advanced color manipulation for node sass
* [benjamindenboer/FramerInput](https://github.com/benjamindenboer/FramerInput) - Design with Inputs in Framer.
* [lauripiispanen/angular-bacon](https://github.com/lauripiispanen/angular-bacon) - Angular-bacon.js bindings
* [slitrobo/framer-path](https://github.com/slitrobo/framer-path) - Create custom svg shapes and animate each point individually in Framer JS.
* [dmotz/hexaflip](https://github.com/dmotz/hexaflip) - 🧊 Visualizes arrays as cube interfaces
* [ffissore/presentz.js](https://github.com/ffissore/presentz.js) - A js library to show synchronized video and slides presentations, powering presentz.org *(archived)*
* [fraserxu/ionic-rating](https://github.com/fraserxu/ionic-rating) - An angularjs directive that take care of visualising a star rating bar
* [Multiply/iron-router-progress](https://github.com/Multiply/iron-router-progress) - Progressbar for iron-router *(archived)*
* [cloudfour/offCanvasMenu](https://github.com/cloudfour/offCanvasMenu) - A jQuery/Zepto plugin that provides an easy way to implement an off-canvas toggling menu, a navigation metaphor made popular by mobile applications.
* [formstamp/formstamp](https://github.com/formstamp/formstamp) - Pure AngularJS widgets
* [hzdg/gsap-react-plugin](https://github.com/hzdg/gsap-react-plugin) - A GSAP plugin for tweening React.js component state.
* [knu/noreferrer](https://github.com/knu/noreferrer) - Cross-browser support for HTML5's noreferrer link type.
* [crashlytics/backbone.statemanager](https://github.com/crashlytics/backbone.statemanager) - Backbone module for adding states to objects *(archived)*
* [ghepting/jquery-responsive-text](https://github.com/ghepting/jquery-responsive-text) - Make your text sizing responsive! *(archived)*
* [KyleAMathews/react-markdown-textarea](https://github.com/KyleAMathews/react-markdown-textarea) - Component for React to create textareas for entering Markdown with built-in preview inspired by Github's design
* [dmotz/maskew](https://github.com/dmotz/maskew) - ▰ Add some diagonal rhythm to your elements
* [steveruizok/gotcha](https://github.com/steveruizok/gotcha) - Turn your Framer prototype into its own live developer spec.
* [der-lukas/framer-Symbols](https://github.com/der-lukas/framer-Symbols) - Create symbols in Framer
* [koding/kd](https://github.com/koding/kd) - UI Framework for web applications. *(archived)*
* [adamalbrecht/ngModal](https://github.com/adamalbrecht/ngModal) - Very basic modal dialog directive for Angular.js *(archived)*
* [avocode/react-universal-router](https://github.com/avocode/react-universal-router) - React router for your web, electron or nw.js app.
* [entroform/stack-up.js](https://github.com/entroform/stack-up.js) - Create fixed width, variable height grid layouts.
* [KyleAMathews/react-micro-bar-chart](https://github.com/KyleAMathews/react-micro-bar-chart) - React component for micro bar-charts rendered with D3
* [ROMB/jquery-dialogextend](https://github.com/ROMB/jquery-dialogextend) - jQuery DialogExtend Plugin - Maximize and Minimize Buttons for UI Dialog
* [Shopify/twine](https://github.com/Shopify/twine) - Twine is a minimalistic two-way binding system
* [ivirabyan/jquery-mentions](https://github.com/ivirabyan/jquery-mentions) - Adds mentioning support to your text fields.
* [jaicab/Paraxify.js](https://github.com/jaicab/Paraxify.js) - Progressive enhancement on parallax inspired by Spotify's
* [magoosh/jquery-infinite-pages](https://github.com/magoosh/jquery-infinite-pages) - Simple infinitely scrolling pages for jQuery, gemified for Rails *(archived)*
* [hzdg/react-google-analytics](https://github.com/hzdg/react-google-analytics) - Google analytics component
* [datapimp/luca](https://github.com/datapimp/luca) - A UI / Component Framework and Application Architecture for Backbone.js which uses twitter's bootstrap for styling
* [72/StickyHeaders-for-Framer](https://github.com/72/StickyHeaders-for-Framer) - A module to create scroll components with sticky headers in Framer.
* [andreypopp/backbone.projections](https://github.com/andreypopp/backbone.projections) - backbone.projections is a set of projections for Backbone.Collection
* [KyleAMathews/react-retina-image](https://github.com/KyleAMathews/react-retina-image) - React component for serving high-resolution images to devices with retina displays
* [brandly/angular-adaptive-backgrounds](https://github.com/brandly/angular-adaptive-backgrounds) - :sunrise_over_mountains: Surround a picture with its dominant color using a simple directive
* [plapier/domflags-extension](https://github.com/plapier/domflags-extension) - A chrome extension to bookmark deeply nested DOM elements
* [joshmtucker/OrientationEvents](https://github.com/joshmtucker/OrientationEvents) - Module for Framer Studio to handle device orientation events.
* [TurkServer/meteor-tutorials](https://github.com/TurkServer/meteor-tutorials) - Create super cool animated tutorials for your Meteor app.
* [maccman/wysiwyg](https://github.com/maccman/wysiwyg)
* [SE7ENSKY/group-css-media-queries](https://github.com/SE7ENSKY/group-css-media-queries) - CSS postprocessing: group media queries. Useful for postprocessing preprocessed CSS files.
* [stakes/fluid-framer](https://github.com/stakes/fluid-framer) - Adds ability to dynamically scale and float elements in the browser window to Framer.js Layers.
* [etiennetalbot/responsImg](https://github.com/etiennetalbot/responsImg) - jQuery plugin to make images load the smallest possible version of itself required for the current viewport size. See it as media queries for img tags.
* [dnagir/knockout-rails](https://github.com/dnagir/knockout-rails) - KnockoutJS for Rails with Sweetness *(archived)*
* [LumaPictures/meteor-jquery-datatables](https://github.com/LumaPictures/meteor-jquery-datatables) - Sort, page, and filter millions of records reactively.
* [anjorweb/fastHtml](https://github.com/anjorweb/fastHtml) - psd 导出 html 的工具
* [avocode/react-droparea](https://github.com/avocode/react-droparea) - Drag and Drop library for React
* [webtempest/meteor-animate](https://github.com/webtempest/meteor-animate) - Easily perform CSS3 animations and transitions in Meteor.
* [marksteve/datamock.js](https://github.com/marksteve/datamock.js) - Adds mock data to your mockups
* [naltatis/node-sprite](https://github.com/naltatis/node-sprite) - A CSS Sprite Generation Library with Stylus and Retina Support.
* [simonexmachina/tabcordion](https://github.com/simonexmachina/tabcordion) - A jQuery plugin that transforms Bootstrap tabs to an accordion and vice versa. Useful for responsive mobile sites.
* [subvisual/meteor-bender](https://github.com/subvisual/meteor-bender) - Animations in page transitions *(archived)*
* [yogiben/meteor-autoform-file](https://github.com/yogiben/meteor-autoform-file) - Upload and manage files with #autoForm
* [KyleAMathews/react-responsive-grid](https://github.com/KyleAMathews/react-responsive-grid) - Power tools for building responsive layouts with React
* [joscha/gmailui](https://github.com/joscha/gmailui) - A GMail user interface library *(archived)*
* [richardbutler/node-spritesheet](https://github.com/richardbutler/node-spritesheet) - Sprite sheet generator for node.js and task for grunt.js
* [salsita/jq-clipthru](https://github.com/salsita/jq-clipthru)
* [markbates/jquery-bootstrap-pagination](https://github.com/markbates/jquery-bootstrap-pagination)
* [KyleAMathews/react-component-gallery](https://github.com/KyleAMathews/react-component-gallery) - React component for creating an evenly spaced gallery of children components
* [ServusJon/SVGCircle-Module-for-FramerJS](https://github.com/ServusJon/SVGCircle-Module-for-FramerJS) - Animate Circles (Strokes) easily.
* [MSchmidt/jquery-fullsizable](https://github.com/MSchmidt/jquery-fullsizable) - Take advantage of full available browser space to display images!
* [amccollum/sel](https://github.com/amccollum/sel) - Sel is a tiny selector engine that has all of the power of Sizzle in about half the code size.
* [bevry-archive/html5edit](https://github.com/bevry-archive/html5edit) - Lightweight R&D project surrounding HTML5's contenteditable feature *(archived)*
* [parrotjs/parrotjs](https://github.com/parrotjs/parrotjs) - Browser features today. High-level wrapper for browser features.
* [jsdf/react-layout](https://github.com/jsdf/react-layout) - Dynamic subview layout for React
* [mycolorway/simple-uploader](https://github.com/mycolorway/simple-uploader) - A HTML5 upload component without UI
* [jawj/github-widget](https://github.com/jawj/github-widget) - Simple script to display own GitHub projects on a webpage, ordered by number of watchers
* [monterail/angular-mighty-datepicker](https://github.com/monterail/angular-mighty-datepicker) - *(archived)*
* [nataliemarleny/Casing](https://github.com/nataliemarleny/Casing) - The UI Framework for Framer Classic. Manages data, components and views *(archived)*
* [RStankov/backbone-bind-to](https://github.com/RStankov/backbone-bind-to) - Backbone.js extension for automatic binding and unbinding of model events to views. *(archived)*
* [SimeonC/ngRepeatReorder](https://github.com/SimeonC/ngRepeatReorder) - *(archived)*
* [ccorcos/meteor-transitioner](https://github.com/ccorcos/meteor-transitioner) - Meteor page transitions integrated with Iron Router.
* [CityBaseInc/formrenderer-base](https://github.com/CityBaseInc/formrenderer-base) - Screendoor's client-side form rendering code.
* [philschatz/css-polyfills.js](https://github.com/philschatz/css-polyfills.js) - :art: Define more with CSS!
* [RStankov/backbone-handlebars](https://github.com/RStankov/backbone-handlebars) - Mixing Backbone and Handlebars *(archived)*
* [acdlite/jquery.sidenotes](https://github.com/acdlite/jquery.sidenotes) - Transform Markdown footnotes into superpowered sidenotes
* [vue-comps/vue-icons](https://github.com/vue-comps/vue-icons) - webpack based - load only what you need - svg inline icons
* [stakes/Framer-VideoPlayer](https://github.com/stakes/Framer-VideoPlayer) - A video player module for Framer Studio and Framer.js.
* [ryhan/guides.js](https://github.com/ryhan/guides.js) - When designing and developing for the web, it's sometimes difficult to follow baselines and precisely align content. Instead of guessing, use guides.js overlay a grid over you HTML while you're working so that you can visually check that everything is aligned perfectly.
* [soyjavi/hamsa](https://github.com/soyjavi/hamsa) - A dead simple, data-binding & observable model.
* [LinkedInAttic/Backbone.TableView](https://github.com/LinkedInAttic/Backbone.TableView) - Backbone View to render collections as tables
* [dmackerman/angular-better-placeholders](https://github.com/dmackerman/angular-better-placeholders) - Angular directive for enhanced placeholders that easily integrate with Bootstrap form fields.
* [icebreaker/proudify](https://github.com/icebreaker/proudify) - jQuery plugin to display your GitHub projects and Coderwall badges
* [teijo/jquery-group](https://github.com/teijo/jquery-group) - Group stage component for tournament play
* [monterail/angular-date-range-picker](https://github.com/monterail/angular-date-range-picker) - Pure Angular date range picker, no jQuery *(archived)*
* [hull/hull-js](https://github.com/hull/hull-js) - The hull.js browser library
* [manuel-schoebel/wait-on-lib](https://github.com/manuel-schoebel/wait-on-lib) - Use Iron-Router waitOn to load external javascript libraries
* [aron/annotator.touch.js](https://github.com/aron/annotator.touch.js) - Touch device support for Annotator
* [ialpert/gridy.js](https://github.com/ialpert/gridy.js) - Gridy.js is a library that can be used in SmartTV's apps. You can use it for carousels, grids, and sliders
* [podlove/podlove-subscribe-button](https://github.com/podlove/podlove-subscribe-button) - Universal button to subscribe to buttons in the desired podcast client or player website
* [joushx/jQuery.EAN13](https://github.com/joushx/jQuery.EAN13) - A jQuery & plain JavaScript library for generating EAN13-barcodes
* [bih/jquery.markdown.js](https://github.com/bih/jquery.markdown.js) - A WYSIWYG Markdown editor built as a jQuery plugin (written in CoffeeScript + SASS). *(archived)*
* [jimjeffers/Easie](https://github.com/jimjeffers/Easie) - Robert Penner's easing equations converted to coffeescript.
* [PayloadDev/react-at-rest](https://github.com/PayloadDev/react-at-rest) - A toolkit for building ridiculously fast web applications using React and RESTful APIs. *(archived)*
* [atom/reactionary](https://github.com/atom/reactionary) - Basic helpers for building React DOM nodes in CoffeeScript. *(archived)*
* [kalasjocke/react-coffee-elements](https://github.com/kalasjocke/react-coffee-elements) - Compact React element syntax when using CoffeeScript.
* [snd/react-kup](https://github.com/snd/react-kup) - react-kup is a simple, nonintrusive alternative to JSX for coffeescript *(archived)*
* [elucidata/react-coffee](https://github.com/elucidata/react-coffee) - Build React components using natural CoffeeScript syntax.
* [ccorcos/meteor-reactive-css](https://github.com/ccorcos/meteor-reactive-css) - Define reactive CSS rules in Javascript or (preferably) Coffeescript.
* [jsdf/flux-coffee](https://github.com/jsdf/flux-coffee) - Implements Facebook's Flux pattern in CoffeeScript
* [leifcr/jquery-csswatch](https://github.com/leifcr/jquery-csswatch) - A CSS Watcher plugin for jquery (Written in CoffeeScript)

### Web Servers and Proxies

* [basecamp/pow](https://github.com/basecamp/pow) - Zero-configuration Rack server for Mac OS X *(archived)*
* [atmos/camo](https://github.com/atmos/camo) - :lock: an http proxy to route images through SSL *(archived)*
* [wearefractal/fusker](https://github.com/wearefractal/fusker) - Fusker is a static HTTP server that provides optional security features for HTTP/Socket.io
* [defvol/Paparazzo.js](https://github.com/defvol/Paparazzo.js) - A high performance web proxy for serving MJPG streams to the masses.
* [jondot/webnull](https://github.com/jondot/webnull) - web/null eats your HTTP
* [bfirsh/otter](https://github.com/bfirsh/otter) - A server that runs your client-side apps.
* [dudleycarr/ratelimit.js](https://github.com/dudleycarr/ratelimit.js) - NodeJS library for rate limiting using sliding windows stored in Redis *(archived)*
* [moviepilot/seoserver](https://github.com/moviepilot/seoserver) - A PhantomjS-based SEO server that serves pages of JavaScript apps to search engine robots like the Googlebot. *(archived)*

### Scraping and Crawling

* [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) - JavaScript API for Chrome and Firefox
* [Tomtomgo/phearjs](https://github.com/Tomtomgo/phearjs) - PhearJS - render dynamic Javascript webpages to JSON with PhantomJS
* [notslang/instagram-screen-scrape](https://github.com/notslang/instagram-screen-scrape) - scrape public instagram data w/out API access
* [nickdima/skrap](https://github.com/nickdima/skrap) - Easily scrap web pages by providing json recipes
* [dobtco/openrfps-scrapers](https://github.com/dobtco/openrfps-scrapers) - Scraping government contracting opportunities.
* [bwbwbwbw/ingress-exporter](https://github.com/bwbwbwbw/ingress-exporter) - Export all portals, links, fields and system broadcasts in a specific area.
* [conancat/fbscrape](https://github.com/conancat/fbscrape) - Facebook Page Photo Scraper in CoffeeScript and NodeJS

## Data and Storage

### Databases

* [twilio/BankersBox](https://github.com/twilio/BankersBox) - redis-like wrapper for javascript storage
* [lmaccherone/node-localstorage](https://github.com/lmaccherone/node-localstorage) - A drop-in substitute for the browser native localStorage API that runs on node.js.
* [dreyacosta/somewhere.js](https://github.com/dreyacosta/somewhere.js) - Small in-memory database for Node.js that persists on disk
* [btwael/locallydb](https://github.com/btwael/locallydb) - An easy-to-use and lightweight local storage database for node.js and node-webkit *(archived)*
* [elcuervo/lodis](https://github.com/elcuervo/lodis) - LOcal Dictionary Server
* [fhirbase/fhirbase-plv8](https://github.com/fhirbase/fhirbase-plv8) - [DEPRECATED] Fhirbase 2.0 is an FHIR relational storage
* [indutny/node-index](https://github.com/indutny/node-index) - Append-only B+ Tree index for node.js

### Database Clients and ORMs

* [thingdom/node-neo4j](https://github.com/thingdom/node-neo4j) - [RETIRED] Neo4j graph database driver (REST API client) for Node.js
* [davidgtonge/backbone_query](https://github.com/davidgtonge/backbone_query) - A lightweight query api for Backbone Collections
* [bevry/query-engine](https://github.com/bevry/query-engine) - QueryEngine provides extensive Querying, Filtering, and Searching abilities for Backbone.js Collections as well as JavaScript arrays and objects
* [stianeikeland/node-etcd](https://github.com/stianeikeland/node-etcd) - :satellite: Etcd client for nodejs
* [emirotin/mongodb-migrations](https://github.com/emirotin/mongodb-migrations) - A Node.js migration framework for MongoDB
* [adaltas/node-hbase](https://github.com/adaltas/node-hbase) - Asynchronous HBase client for NodeJs using REST
* [vidigami/backbone-orm](https://github.com/vidigami/backbone-orm) - A polystore ORM for Node.js and the browser
* [marckrenn/framer-Firebase](https://github.com/marckrenn/framer-Firebase) - The Firebase module allows your Framer prototype to load, save and sync data effortlessly between multiple sessions and devices.
* [wspringer/angular-pouchdb](https://github.com/wspringer/angular-pouchdb) - Angular wrapper for PouchDB, making sure that callbacks are called within $rootScope.$apply(), and using $q promises instead of callbacks. On top of that, it supports an `ng-repeat`-alike directive for traversing the contents of your database.
* [victorquinn/dynasty](https://github.com/victorquinn/dynasty) - Dynasty - Promise-based, clean DynamoDB API
* [vsivsi/meteor-file-collection](https://github.com/vsivsi/meteor-file-collection) - Extends Meteor Collections to handle file data using MongoDB gridFS.
* [ccorcos/meteor-any-db](https://github.com/ccorcos/meteor-any-db) - A database API for Meteor
* [yang/rel](https://github.com/yang/rel) - Arel ported to node js — with some changes *(archived)*
* [nicklandgrebe/active-resource.js](https://github.com/nicklandgrebe/active-resource.js) - ActiveResource.js - API resource relational mapping in JavaScript
* [lessthan3/mongofb](https://github.com/lessthan3/mongofb) - MongoFirebase - MongoDB + Firebase security/updates
* [peerlibrary/meteor-peerdb](https://github.com/peerlibrary/meteor-peerdb) - Reactive database layer with references, generators, triggers, migrations, etc.
* [tglines/dynasaur](https://github.com/tglines/dynasaur) - DynamoDB ORM for Node.js
* [awwx/meteor-offline-data](https://github.com/awwx/meteor-offline-data) - Meteor offline data project.
* [linus/refix](https://github.com/linus/refix) - A redis client proxy, which prefixes all keys with the given string
* [cretz/node-tds](https://github.com/cretz/node-tds) - Pure JS implementation of TDS protocol for Microsoft SQL Server
* [Exygy/minimongoid](https://github.com/Exygy/minimongoid) - Mongoid inspired model architecture for your Meteor apps.
* [TorchlightSoftware/mongo-watch](https://github.com/TorchlightSoftware/mongo-watch) - Watches for changes in MongoDB replication log.
* [wearefractal/crudify](https://github.com/wearefractal/crudify) - Mongoose CRUD generator
* [pstaender/mongraph](https://github.com/pstaender/mongraph) - Mongraph combines documentstorage database with graph-database relations. Build on NodeJS. *(archived)*
* [meltingice/node-activerecord](https://github.com/meltingice/node-activerecord) - A ORM written in Coffeescript that supports multiple database systems (SQL/NoSQL) and ID generation middleware.
* [falsecz/hbase-rpc-client](https://github.com/falsecz/hbase-rpc-client) - CoffeeScript HBase client implementation with protobuf support
* [wvanbergen/node-vertica](https://github.com/wvanbergen/node-vertica) - Pure javascript Vertica database client. Except it is written in CoffeeScript.
* [rbrcurtis/cofmon](https://github.com/rbrcurtis/cofmon) - A coffeescript shell for mongodb.
* [Radagaisus/Orpheus](https://github.com/Radagaisus/Orpheus) - A Small Object Model for Redis in CoffeeScript *(archived)*
* [boiawang/sequelize-db-export-import](https://github.com/boiawang/sequelize-db-export-import) - Generater models from mysql db or import tables from models files
* [naturalethic/coffee-mongo](https://github.com/naturalethic/coffee-mongo) - Model framework for Node.js + CoffeeScript + MongoDB
* [agoragames/leaderboard-coffeescript](https://github.com/agoragames/leaderboard-coffeescript) - Leaderboards backed by Redis in CoffeeScript
* [jysperm/Mabolo](https://github.com/jysperm/Mabolo) - Just a simple ORM of MongoDB API.
* [sergeych/node-prego](https://github.com/sergeych/node-prego) - Minimalistic migrations & models for coffeescript, node.js and postgres

### Serialization and Formats

* [Leonidas-from-XIV/node-xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.
* [bevry/cson](https://github.com/bevry/cson) - CoffeeScript-Object-Notation. Same as JSON but for CoffeeScript objects.
* [oozcitak/xmlbuilder-js](https://github.com/oozcitak/xmlbuilder-js) - An XML builder for node.js
* [jeremyfa/yaml.js](https://github.com/jeremyfa/yaml.js) - Standalone JavaScript YAML 1.2 Parser & Encoder. Works under node.js and all major browsers. Also brings command line YAML/JSON conversion tools.
* [edemaine/fold](https://github.com/edemaine/fold) - FOLD file format for origami models, crease patterns, etc.
* [jsog/jsog](https://github.com/jsog/jsog) - JavaScript Object Graph
* [joelvh/json2json](https://github.com/joelvh/json2json) - Transform (reformat) JSON structures from one to another using JavaScript
* [chuanyi/msexcel-builder](https://github.com/chuanyi/msexcel-builder) - A simple and fast library to create MS Office Excel(>2007) xlsx files.
* [pandastrike/jsck](https://github.com/pandastrike/jsck) - JSON Schema Compiled checK
* [mirek/node-rus-diff](https://github.com/mirek/node-rus-diff) - JSON diff
* [stevetarver/excel-as-json](https://github.com/stevetarver/excel-as-json) - npm package that converts excel data to json
* [jonahkagan/schematic-ipsum](https://github.com/jonahkagan/schematic-ipsum) - A simple service that generates fake JSON data in accordance with a JSON Schema
* [cubehero/stljs](https://github.com/cubehero/stljs) - Read and write STL (3D printable model) files to your heart's content
* [grmble/node-dicom](https://github.com/grmble/node-dicom) - DICOM utils/parser for node.js
* [atom/season](https://github.com/atom/season) - CSON Node Module *(archived)*
* [elistevens/xws-spec](https://github.com/elistevens/xws-spec) - X-Wing Squadron Specification
* [nickdesaulniers/javascript-playlist-parser](https://github.com/nickdesaulniers/javascript-playlist-parser) - Parse m3u, pls, and asx in JavaScript
* [rastapasta/tilegrinder](https://github.com/rastapasta/tilegrinder) - ♻️ A node.js GIS helper library for easy alteration of Vector Tiles in an MBTiles container
* [devongovett/coffeepack](https://github.com/devongovett/coffeepack) - An implementation of the MessagePack serialization format in CoffeeScript for Node.js and the browser.

### Caching and Queues

* [node-cache/node-cache](https://github.com/node-cache/node-cache) - a node internal (in-memory) caching module
* [technoweenie/coffee-resque](https://github.com/technoweenie/coffee-resque)
* [vsivsi/meteor-job-collection](https://github.com/vsivsi/meteor-job-collection) - A persistent and reactive job queue for Meteor, supporting distributed workers that can run anywhere.
* [conancat/mongoose-redis-cache](https://github.com/conancat/mongoose-redis-cache) - Cache your Mongoose MongoDB query results with Redis. 300% faster queries FTW!
* [mpneuried/rsmq-worker](https://github.com/mpneuried/rsmq-worker) - Helper to simply implement a worker around RSMQ ( Redis Simple Message Queue )
* [loopj/node-sidekiq](https://github.com/loopj/node-sidekiq) - Enqueue jobs to sidekiq from your node apps. Closely mirrors the official ruby sidekiq interface and supports job scheduling.
* [Differential/meteor-workers](https://github.com/Differential/meteor-workers) - Spawn headless worker meteor processes to work on async jobs.
* [yi/node-ticket-manager](https://github.com/yi/node-ticket-manager) - a simple ticket system contians a centeral ticket dispatcher and distributed workers. This system is written in NodeJS, runing on MongoDB *(archived)*
* [dropbox/amqp-coffee](https://github.com/dropbox/amqp-coffee) - An AMQP 0.9.1 client for Node.js.
* [kmalakoff/background](https://github.com/kmalakoff/background) - CoffeeScript / JavaScript background job / task / worker library. Provides implementations for jobs, a job queue, a job list, and single and multiple array iterators.

## Machine Learning and AI

### Computer Vision

* [creatale/node-fv](https://github.com/creatale/node-fv) - A node.js library for extracting data from scanned forms.
* [yuta1984/CannyJS](https://github.com/yuta1984/CannyJS) - A client-side JavaScript implementation of Canny Edge Detection
* [seanbell/opensurfaces-segmentation-ui](https://github.com/seanbell/opensurfaces-segmentation-ui) - Segmentation UI from the OpenSurfaces Project
* [nok/onedollar-unistroke-coffee](https://github.com/nok/onedollar-unistroke-coffee) - Implementation of the $1 Unistroke Recognizer, a two-dimensional template based gesture recognition, in CoffeeScript. *(archived)*
* [steelThread/mimeograph](https://github.com/steelThread/mimeograph) - CoffeeScript lib for PDF OCR and text extraction

### Natural Language Processing

* [lissy93/twitter-sentiment-visualisation](https://github.com/lissy93/twitter-sentiment-visualisation) - 🌍 Sentiment analysis over real-time social media data, rendering live charts to visualise trends
* [xissy/node-stanford-simple-nlp](https://github.com/xissy/node-stanford-simple-nlp) - A simple node.js wrapper for stanford-core-nlp.
* [ageitgey/node-pullquoter](https://github.com/ageitgey/node-pullquoter) - Automatically pull interesting quotes out of an article.
* [dotcypress/aiml](https://github.com/dotcypress/aiml) - [Deprecated] Artificial Intelligence Markup Language lib for Node.js
* [ethel-dev/sentimood](https://github.com/ethel-dev/sentimood) - A minimal sentiment analyzer based on @thinkroth's "Sentimental" and written in CoffeeScript

### Data Science and Analytics

* [nicolaskruchten/pivottable](https://github.com/nicolaskruchten/pivottable) - Open-source Javascript Pivot Table (aka Pivot Grid, Pivot Chart, Cross-Tab) implementation with drag'n'drop.
* [ExpediaGroup/cyclotron](https://github.com/ExpediaGroup/cyclotron) - A web platform for constructing dashboards.
* [agmen-hu/node-datapumps](https://github.com/agmen-hu/node-datapumps) - Node.js ETL (Extract, Transform, Load) toolkit for easy data import, export or transfer between systems.
* [tamc/Sankey](https://github.com/tamc/Sankey) - A javascript library for drawing sankey / flow diagrams
* [h2oai/h2o-flow](https://github.com/h2oai/h2o-flow) - Web based interactive computing environment for H2O
* [vlandham/gates_bubbles](https://github.com/vlandham/gates_bubbles) - animated bubble charts in D3
* [vogievetsky/DVL](https://github.com/vogievetsky/DVL) - Dynamic Visualization LEGO
* [HazyResearch/mindbender](https://github.com/HazyResearch/mindbender) - Tools for iterative knowledge base development with DeepDive
* [nagarajanchinnasamy/subtotal](https://github.com/nagarajanchinnasamy/subtotal) - A JavaScript plugin for PivotTable.js. It renders subtotals of rows and columns with the ability to expand and collapse rows and columns
* [loule/js-chart-widgets](https://github.com/loule/js-chart-widgets)
* [lmaccherone/documentdb-lumenize](https://github.com/lmaccherone/documentdb-lumenize) - Aggregations (Group-by, Pivot-table, and N-dimensional Cube) and Time Series Transformations as Stored Procedures in DocumentDB
* [kbroman/d3panels](https://github.com/kbroman/d3panels) - A library of d3-based graphic panels, written in CoffeeScript
* [NarendraYSF/WorkFlowViz](https://github.com/NarendraYSF/WorkFlowViz) - Transform your task data into interactive workflow visualizations with a single line of code. WorkflowViz.js is a lightweight JavaScript library that helps you create beautiful, dynamic flowcharts to track project progress, visualize task dependencies, and highlight important milestones.

## Networking and Distributed

### Networking

* [alexkirsz/dispatch-proxy](https://github.com/alexkirsz/dispatch-proxy) - Combine internet connections, increase your download speed *(archived)*
* [shadowsocks/shadowsocks-gui](https://github.com/shadowsocks/shadowsocks-gui) - Shadowsocks GUI client
* [okTurtles/dnschain](https://github.com/okTurtles/dnschain) - A blockchain-based DNS + HTTP server that fixes HTTPS security, and more!
* [shadowsocks/shadowsocks-nodejs](https://github.com/shadowsocks/shadowsocks-nodejs)
* [shadowsocks/shadowsocks-chromeapp](https://github.com/shadowsocks/shadowsocks-chromeapp) - Chrome client for shadowsocks
* [whitequark/ipaddr.js](https://github.com/whitequark/ipaddr.js) - IP address manipulation library in JavaScript
* [josephg/node-browserchannel](https://github.com/josephg/node-browserchannel) - An implementation of a google browserchannel server in node.js
* [FurqanSoftware/node-whois](https://github.com/FurqanSoftware/node-whois) - A simple WHOIS client for NodeJS
* [yakyak/hangupsjs](https://github.com/yakyak/hangupsjs) - google hangouts client library for nodejs
* [521xueweihan/shadowsocks-heroku](https://github.com/521xueweihan/shadowsocks-heroku) - 本项目已删除
* [shadowsocks/shadowsocks-dotcloud](https://github.com/shadowsocks/shadowsocks-dotcloud) - a port of shadowsocks via websockets protocol, able to tunnel through HTTP proxy
* [msolters/wifi-control-node](https://github.com/msolters/wifi-control-node) - A NodeJS module that allows you to scan for, connect to and disconnect from wireless access points near the server. Great for offline or local apps.
* [buddycloud/deprecated-buddycloud-server](https://github.com/buddycloud/deprecated-buddycloud-server) - A buddycloud server written in Node.
* [joyqi/socket-pipe](https://github.com/joyqi/socket-pipe)
* [circuithub/mail-listener](https://github.com/circuithub/mail-listener) - Mail listener library for node.js. Get notification when new email arrived.
* [moul/iocat](https://github.com/moul/iocat) - :wrench: Socket.io & WebSocket netcat-like utility
* [realtymaps/promise-ftp](https://github.com/realtymaps/promise-ftp) - a promise-based ftp client for node.js
* [foxdog-studios/meteor-webrtc](https://github.com/foxdog-studios/meteor-webrtc) - WebRTC signalling for Meteor
* [ppmathis/sync.io](https://github.com/ppmathis/sync.io) - Open-source BitTorrent Sync tracker and relay server which features a web status page.
* [jacobrask/node-upnp-device](https://github.com/jacobrask/node-upnp-device) - Create UPnP devices in Node.js (experimental)
* [cmp-202/ssh2shell](https://github.com/cmp-202/ssh2shell) - Wrapper class for Node.js ssh2 shell command for running multiple commands
* [7anshuai/masq](https://github.com/7anshuai/masq) - Simple local DNS server for using *.dev domains
* [Quobis/QoffeeSIP](https://github.com/Quobis/QoffeeSIP) - QoffeeSIP is a complete Javascript SIP stack that can be used in a website to exploit all the multimedia capabilities of WebRTC technology. Instead of using pure Javascript, QoffeeSIP has been coded with CoffeeScript so you can easily modify it to suit your needs. *(archived)*

### Cloud and Infrastructure

* [lucasmotta/dploy](https://github.com/lucasmotta/dploy) - ⛔️ currently unmaintained ⛔️
* [segmentfault/deploy-robot](https://github.com/segmentfault/deploy-robot) - GitHub 自动部署机器人
* [Lepozepo/S3](https://github.com/Lepozepo/S3) - A simple helper for easily uploading files to Amazon S3 from Meteor. This package will also make Knox available server-side.
* [overleaf/docker-image](https://github.com/overleaf/docker-image) - A Dockerfile for building the official Overleaf Community Edition docker image *(archived)*
* [andruschka/pm2-meteor](https://github.com/andruschka/pm2-meteor) - Simplest way to deploy, scale and run Meteor Apps with PM2.
* [google-fabric/galley](https://github.com/google-fabric/galley) - Orchestrator for local Docker containers *(archived)*
* [HackPlan/RootPanel](https://github.com/HackPlan/RootPanel) - A pluggable PaaS service development framework.
* [tadruj/s3upload-coffee-javascript](https://github.com/tadruj/s3upload-coffee-javascript) - Client Side S3 CORS Upload for Amazon S3 - CoffeeScript and JavaScript Class
* [inossidabile/grunt-ftpush](https://github.com/inossidabile/grunt-ftpush) - Grunt task for incremental code deployment over ftp
* [cloudfoundry-community/node-cfenv](https://github.com/cloudfoundry-community/node-cfenv) - easy access to your Cloud Foundry application environment for node
* [tiagoboldt/sharelatex-docker](https://github.com/tiagoboldt/sharelatex-docker) - Sharelatex instalation via Dockerfile *(archived)*
* [horatio-sans-serif/linode-api](https://github.com/horatio-sans-serif/linode-api) - Linode API client for Node.js
* [mazehall/eintopf](https://github.com/mazehall/eintopf) - The smartest way to share and administrate docker projects. *(archived)*
* [docpad/docpad-plugin-ghpages](https://github.com/docpad/docpad-plugin-ghpages) - Deploy your DocPad Website to GitHub Pages

### Monitoring and Observability

* [HubSpot/BuckyClient](https://github.com/HubSpot/BuckyClient) - Collect performance data from the client
* [HubSpot/BuckyServer](https://github.com/HubSpot/BuckyServer) - Node server that receives metric data over HTTP & forwards to your service of choice *(archived)*
* [coredump/hoardd](https://github.com/coredump/hoardd) - Hoardd is extensible daemon designed to collect server data and inject into Graphite/Carbon *(archived)*
* [superstringsoftware/observatory](https://github.com/superstringsoftware/observatory) - Powerful, yet easy to use, logging, monitoring and application management package for Meteor framework. Some docs below, for details -
* [sensu/sensu-dashboard](https://github.com/sensu/sensu-dashboard) - A dashboard for Sensu, for displaying & managing events & clients. *(archived)*
* [olark/hashmonitor](https://github.com/olark/hashmonitor) - turn logs into metrics like a boss
* [plainlystated/coffeescript-rrd](https://github.com/plainlystated/coffeescript-rrd) - coffeescript library for using manipulating RRD files (depends on rrdtool)

## User Interface

### Mobile

* [openstf/adbkit](https://github.com/openstf/adbkit) - A pure Node.js client for the Android Debug Bridge.
* [dmotz/natal](https://github.com/dmotz/natal) - 📲 Bootstrap ClojureScript React Native apps
* [ai/compass.js](https://github.com/ai/compass.js) - Compass.js allow you to get compass heading in JavaScript by PhoneGap, iOS API or GPS hack.
* [jtomaszewski/ionic-cordova-gulp-seed](https://github.com/jtomaszewski/ionic-cordova-gulp-seed) - Ionic & Cordova & Gulp combo-seed - perfect for starting with Ionic framework!
* [facebookarchive/ios-11-gui-for-framer](https://github.com/facebookarchive/ios-11-gui-for-framer) - Components that make it easy for designers to quickly prototype native-feeling iOS 11 interactions in Framer *(archived)*
* [AppGyver/steroids-js](https://github.com/AppGyver/steroids-js) - DEPRECATED PROJECT <> Steroids JavaScript Library *(archived)*
* [maccman/spine.mobile](https://github.com/maccman/spine.mobile) - Spine Mobile Framework
* [wongpeiyi/flipium](https://github.com/wongpeiyi/flipium) - Flipboard-style UI element for Titanium Appcelerator, written in Coffeescript

### Applications and End User Tools

* [atom/atom](https://github.com/atom/atom) - :atom: The hackable text editor *(archived)*
* [FelisCatus/SwitchyOmega](https://github.com/FelisCatus/SwitchyOmega) - No longer maintained, see pinned issues
* [yakyak/yakyak](https://github.com/yakyak/yakyak) - Desktop chat client for Google Hangouts
* [Pagedraw/pagedraw](https://github.com/Pagedraw/pagedraw) - a UI builder for React web apps
* [paradoxxxzero/butterfly](https://github.com/paradoxxxzero/butterfly) - A web terminal based on websocket and tornado
* [jianliaoim/talk-os](https://github.com/jianliaoim/talk-os) - Open source version of jianliao.com
* [jkbrzt/cloudtunes](https://github.com/jkbrzt/cloudtunes) - Web-based music player for the cloud :cloud: :notes: Play music from YouTube, Dropbox, etc.
* [akhodakivskiy/VimFx](https://github.com/akhodakivskiy/VimFx) - Vim keyboard shortcuts for Firefox
* [replit-archive/repl.it](https://github.com/replit-archive/repl.it) - https://repl.it/feedback Online REPL for 15+ languages. *(archived)*
* [artursapek/mondrian](https://github.com/artursapek/mondrian) - Web-based vector graphics editor *(archived)*
* [ccd0/4chan-x](https://github.com/ccd0/4chan-x) - Adds various features to anonymous imageboards.
* [cdglabs/apparatus](https://github.com/cdglabs/apparatus) - A hybrid graphics editor and programming environment for creating interactive diagrams.
* [bucketsio/buckets](https://github.com/bucketsio/buckets) - [DEPRECATED] Manage content better. *(archived)*
* [joyqi/sfz](https://github.com/joyqi/sfz) - 专门用于给图片加水印打码的工具，完全基于浏览器本地API，无任何网络请求（特别适合身份证等敏感证件）
* [Atraci/Atraci](https://github.com/Atraci/Atraci) - Free music streaming player
* [JoelBesada/pasteboard](https://github.com/JoelBesada/pasteboard) - Clipboard and drag & drop image sharing web app
* [artsy/force](https://github.com/artsy/force) - The Artsy.net website
* [jinzhu/vrome](https://github.com/jinzhu/vrome) - Vrome: Bringing Vim elegance to Chrome
* [filearts/plunker](https://github.com/filearts/plunker) - Plnkr.co front-end and backend *(archived)*
* [spsdco/notes](https://github.com/spsdco/notes) - Awesome note taking.
* [meltingice/CoffeeDrop](https://github.com/meltingice/CoffeeDrop) - CoffeeDrop is an open-source, roll your own, Dropbox-like clone written in CoffeeScript. Currently not working and under heavy development.
* [AriaMinaei/Griddify](https://github.com/AriaMinaei/Griddify) - A tiny Photoshop panel to make guides and grids
* [Illyism/musicplayer.io](https://github.com/Illyism/musicplayer.io) - :musical_note: A free and open-source streaming music web player using data from Reddit
* [cben/mathdown](https://github.com/cben/mathdown) - Collaborative markdown with math
* [qq99/echoplexus](https://github.com/qq99/echoplexus) - Socket.io powered chat, JavaScript REPL, whiteboard, and WebRTC calls
* [felixhageloh/uebersicht-widgets](https://github.com/felixhageloh/uebersicht-widgets) - A collection of community widgets for Übersicht
* [davidedc/livecodelab](https://github.com/davidedc/livecodelab) - a web based livecoding environment
* [qrpike/spotify-playlist-downloader](https://github.com/qrpike/spotify-playlist-downloader) - Download an entire spotify playlist ( FROM SPOTIFY at 160kpbs ) to your local machine.
* [bradjasper/subtle-patterns-bookmarklet](https://github.com/bradjasper/subtle-patterns-bookmarklet) - SubtlePatterns Bookmarklet
* [postcasio/hearthdash](https://github.com/postcasio/hearthdash) - Hearthstone tracker
* [yui540/satella.io](https://github.com/yui540/satella.io) - イラストに「命」を吹き込むソフトウェア *(archived)*
* [rscarvalho/pyregex](https://github.com/rscarvalho/pyregex) - pyregex is a Python Regular Expression Online Tester
* [filearts/plunker_www](https://github.com/filearts/plunker_www) - The public-facing website for http://plnkr.co *(archived)*
* [edemaine/coauthor](https://github.com/edemaine/coauthor) - Coauthor supercollaboration/discussion forum
* [peerlibrary/peerlibrary](https://github.com/peerlibrary/peerlibrary) - Facilitating the global conversation on academic literature
* [xuender/cm](https://github.com/xuender/cm) - Google Chrome extension ContextMenus
* [k2nr/ViChrome](https://github.com/k2nr/ViChrome) - vi like key binds for Google Chrome
* [edemaine/cocreate](https://github.com/edemaine/cocreate) - Cocreate Shared Whiteboard/Drawing
* [bkeepers/github-notifications](https://github.com/bkeepers/github-notifications) - A client for reading GitHub notifications *(archived)*
* [jdleesmiller/jotgit](https://github.com/jdleesmiller/jotgit) - Git-backed real time collaborative editor built with meteor.
* [revir/FairyDict](https://github.com/revir/FairyDict) - FairyDict, a dictionary, a chrome extension
* [ppzreboot/epub-viewer](https://github.com/ppzreboot/epub-viewer) - epub 阅读器
* [increments/kobito-oss](https://github.com/increments/kobito-oss) - Markdown Processor built on Electron based on kobito-for-windows *(archived)*
* [tylerlong/slim_text](https://github.com/tylerlong/slim_text) - Slim Text Editor
* [bibviz/bibviz](https://github.com/bibviz/bibviz) - BibViz.com Website and Scripts
* [herrbischoff/nerdbar.widget](https://github.com/herrbischoff/nerdbar.widget) - Übersicht system information bar for use with kwm window manager (or without). *(archived)*
* [layerssss/manager-for-upyun](https://github.com/layerssss/manager-for-upyun) - 又拍云资源管理器
* [chuangbo/meteor-bbs](https://github.com/chuangbo/meteor-bbs) - A Clone of Project Babel 3 in Meteor *(archived)*
* [STRd6/pixel-editor](https://github.com/STRd6/pixel-editor) - It edits pixels
* [HubSpot/facewall](https://github.com/HubSpot/facewall) - Grid visualization of Gravatars for an organization *(archived)*
* [lucaspiller/shortly](https://github.com/lucaspiller/shortly) - Shortly: a Serverless Pastebin Service - All Data is Stored in the URL
* [sn-o-w/ZeroOmega](https://github.com/sn-o-w/ZeroOmega)
* [yui540/toa](https://github.com/yui540/toa) - シンプルで可愛いミュージックプレイヤー「兎亜」 *(archived)*
* [marekhrabe/messenger](https://github.com/marekhrabe/messenger) - Unofficial Facebook Mesenger for Mac *(archived)*
* [zixaphir/appchan-x](https://github.com/zixaphir/appchan-x) - The most comprehensive, feature filled 4chan userscript.
* [apierz/nerdbar.widget](https://github.com/apierz/nerdbar.widget) - Customizable bar(s) for OSX.
* [frankleenaars/gearsketch](https://github.com/frankleenaars/gearsketch) - GearSketch sandbox in CoffeeScript
* [bitoiu/github-red-alert](https://github.com/bitoiu/github-red-alert) - Changes the GitHub notification icon to red if you have unread participating notifications.
* [rizzoma/rizzoma](https://github.com/rizzoma/rizzoma) - Code that powers Rizzoma collaboration platform
* [oott123/Slash](https://github.com/oott123/Slash) - Read your documents cross platform.
* [janraasch/tab-ahead](https://github.com/janraasch/tab-ahead) - Web Browser Extension that helps you to quickly find open tabs by title and URL.
* [yui540/wakaba](https://github.com/yui540/wakaba) - PC画面上にコメントが流せるデスクトップアプリ「若葉」
* [iv-one/coursera-downloader](https://github.com/iv-one/coursera-downloader) - Coursera Videos Downloader Chrome Plugin *(archived)*
* [greneholt/youtube5](https://github.com/greneholt/youtube5) - Safari extension that converts YouTube videos on any site into HTML5 video tags
* [michaelvillar/photoslog](https://github.com/michaelvillar/photoslog) - A simple page to show a log of your photos.
* [Considerit/ConsiderIt](https://github.com/Considerit/ConsiderIt) - For deliberation and opinion visualization
* [TurkServer/CrowdMapper](https://github.com/TurkServer/CrowdMapper) - Real-time collaborative application for tagging streams of geospatial data, built on top of the Meteor Javascript platform. Built with the humanitarian goal of crisis mapping in mind.
* [geordanr/xwing](https://github.com/geordanr/xwing) - Squad builder for the First Edition X-Wing Miniatures game by Fantasy Flight Games.
* [butterproject/butter-desktop-angular](https://github.com/butterproject/butter-desktop-angular) - Angular version of butter-desktop
* [gronostajo/drill2](https://github.com/gronostajo/drill2) - Browser-based multiple choice test learning assistant
* [yui540/Shuvi](https://github.com/yui540/Shuvi) - フレームレスなYouTubeプレイヤー「Shuvi」 *(archived)*
* [opinsys/walma](https://github.com/opinsys/walma) - Collaborative Whiteboard *(archived)*
* [subvisual/tripl.it](https://github.com/subvisual/tripl.it) - A mobile application for sharing trip expenses with friends. Made with Meteor. *(archived)*
* [mr-mig/webbooost](https://github.com/mr-mig/webbooost) - Chrome extension for faster web browsing.
* [tent/tent-status](https://github.com/tent/tent-status) - Microblogging powered by Tent *(archived)*
* [oliversong/fortnight](https://github.com/oliversong/fortnight) - A scoped, heatmapping, load-balancing todo list.
* [blahsd/supernerd.widget](https://github.com/blahsd/supernerd.widget) - Extensible, customisable, menubar replacement Ubersicht widget.
* [markuso/kleks](https://github.com/markuso/kleks) - Kleks - Pure CouchDB based CMS as a Couch App using Kanso with CoffeeScript and Stylus. Supports multi-site setup and Markdown authoring. *(archived)*
* [hashify/hashify.me](https://github.com/hashify/hashify.me) - Store entire documents in URLs
* [ujiro99/RedmineTimeTracker](https://github.com/ujiro99/RedmineTimeTracker) - Chrome/Electron app for tracking work time. *(archived)*
* [linus/fullzurf](https://github.com/linus/fullzurf) - Chrome optimized for full-screen
* [linus/foforous](https://github.com/linus/foforous) - Frontend for a Posterous blog, running on Node
* [jeticg/Evangelion-Uebersicht-Widget](https://github.com/jeticg/Evangelion-Uebersicht-Widget) - Evangelion Style Übersicht Widget.
* [frankrousseau/kyou](https://github.com/frankrousseau/kyou) - With Kyou, have a better knowledge of yourself
* [lotem/rimekit](https://github.com/lotem/rimekit) - Rime Kit （已棄坑）
* [forabi/aQuran](https://github.com/forabi/aQuran) - A mobile-optimized, cross-platform Quran app built with web technologies.
* [nornagon/ircv](https://github.com/nornagon/ircv) - IRC inna Chrome app
* [dennisreimann/Codeshelver](https://github.com/dennisreimann/Codeshelver) - Codeshelver lets you clean up your GitHub watchlist by storing repositories you would like to remember on your shelf. *(archived)*
* [andrewminer/crafting-guide](https://github.com/andrewminer/crafting-guide) - The ultimate step-by-step guide to make anything in Minecraft *(archived)*
* [cozy/cozy-emails](https://github.com/cozy/cozy-emails) - Email Client for Cozy *(archived)*
* [felixhageloh/weather-widget](https://github.com/felixhageloh/weather-widget) - A weather widget for Übersicht
* [ferro/ferro](https://github.com/ferro/ferro) - Do stuff with your keyboard in Chrome
* [cnodejs/cnodejs-reader](https://github.com/cnodejs/cnodejs-reader) - CNode.js reader in React
* [HelloZeroNet/ZeroTalk](https://github.com/HelloZeroNet/ZeroTalk) - ZeroTalk
* [nylas/N1-Markdown-Composer](https://github.com/nylas/N1-Markdown-Composer) - An N1 plugin to write emails using markdown
* [ttscoff/ubersicht-widgets](https://github.com/ttscoff/ubersicht-widgets)
* [neelabhg/currency-arbitrage-graph](https://github.com/neelabhg/currency-arbitrage-graph) - Visualize arbitrage opportunities in foreign currency exchange.
* [SyntaxColoring/Markov-Word-Generator](https://github.com/SyntaxColoring/Markov-Word-Generator) - A web app that uses Markov chains to generate pseudorandom words.
* [georgeOsdDev/slidepad](https://github.com/georgeOsdDev/slidepad) - HTML Slide Generator.
* [stephenmcd/grillode](https://github.com/stephenmcd/grillode) - A web-based chat application written in CoffeeScript for Node.js
* [mkilling/alfamegle](https://github.com/mkilling/alfamegle) - cheap omegle clone in CoffeeScript using Socket.IO
* [klen/mahjong.horneds.com](https://github.com/klen/mahjong.horneds.com) - Riichi Mahjong Scores Trainer
* [rbrcurtis/Brewer](https://github.com/rbrcurtis/Brewer) - a split-pane coffeescript editor that shows the compiled js using the ace editor
* [soswow/lobzik](https://github.com/soswow/lobzik) - Simple application for testing employee candidate code skills and knowledge. Currently it's more suitable for testing front-end, JavaScript/CoffeeScript developers.
* [jawj/pigeonsim](https://github.com/jawj/pigeonsim) - Fly! Courtesy of this small project linking Kinect -> OpenNI -> Processing -> WebSockets -> CoffeeScript -> Google Earth API
* [koostudios/kel](https://github.com/koostudios/kel) - A ridiculously simple markdown file-based website system built on Express, CoffeeScript and NodeJS

## Graphics and Media

### Graphics and Rendering

* [gka/chroma.js](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations
* [morrisjs/morris.js](https://github.com/morrisjs/morris.js) - Pretty time-series line graphs
* [kartograph/kartograph.js](https://github.com/kartograph/kartograph.js) - UNMAINTAINED Open source JavaScript renderer for Kartograph SVG maps
* [literallycanvas/literallycanvas](https://github.com/literallycanvas/literallycanvas) - A canvas in your browser. Literally. *(archived)*
* [pyalot/webgl-heatmap](https://github.com/pyalot/webgl-heatmap) - A high performance WebGL/JS heatmap display library
* [williamngan/pt](https://github.com/williamngan/pt) - An experimental library on point, form, and space.
* [GraphAlchemist/Alchemy](https://github.com/GraphAlchemist/Alchemy)
* [c0bra/color-scheme-js](https://github.com/c0bra/color-scheme-js) - Generate pleasant color schemes in JavaScript
* [tmtk75/jumly](https://github.com/tmtk75/jumly) - Rendering engine for UML diagrams in JavaScript *(archived)*
* [mobomo/sketch.js](https://github.com/mobomo/sketch.js) - A jQuery plugin for dead simple Canvas-based drawing.
* [edvakf/MMD.js](https://github.com/edvakf/MMD.js) - MikuMikuDance on WebGL
* [fw42/honeymap](https://github.com/fw42/honeymap) - Real-time websocket stream of GPS events on a fancy SVG world map
* [jonastreub/VRComponent](https://github.com/jonastreub/VRComponent) - A virtual reality component for Framer.
* [sshirokov/ThreeBSP](https://github.com/sshirokov/ThreeBSP) - CSG with Three.js geometries
* [judnich/Kosmos](https://github.com/judnich/Kosmos) - A virtual 3D universe in your web browser.
* [dbushong/shaky](https://github.com/dbushong/shaky) - Converted dart shaky boxes demo to coffeescript
* [soulwire/Plasmatic-Isosurface](https://github.com/soulwire/Plasmatic-Isosurface) - A 2 dimensional plasma simulation running on the GPU, written in GLSL and CoffeeScript and rendered with WebGL.
* [ndrwhr/tumbler](https://github.com/ndrwhr/tumbler) - A simple physics simulation/meditation/relaxation experiment.
* [SoftwareBrothers/fabricjs-viewport](https://github.com/SoftwareBrothers/fabricjs-viewport) - allows zooming and viewport manipulation in fabricjs
* [larspetrus/Roofpig](https://github.com/larspetrus/Roofpig) - Rubik's Cube animation for the modern web.
* [leapmotion/leapjs-rigged-hand](https://github.com/leapmotion/leapjs-rigged-hand) - Control hand models with the Leap Motion
* [sinisterchipmunk/jax](https://github.com/sinisterchipmunk/jax) - Framework for creating rich WebGL-enabled applications using JavaScript and Ruby
* [blakecarroll/particle-saga](https://github.com/blakecarroll/particle-saga) - A gallery for images and models rendered as particles with three.js
* [etiennepinchon/hologram](https://github.com/etiennepinchon/hologram) - Hologram Framework | All-in-one WebVR creation.
* [edemaine/svgtiler](https://github.com/edemaine/svgtiler) - Tool for drawing diagrams on a grid, combining grids of SVGs into a big SVG figure
* [davidguttman/wave-pendulum](https://github.com/davidguttman/wave-pendulum) - simple html 5 wave pendulum using coffeescript and processing.js
* [dkln/canvas_library](https://github.com/dkln/canvas_library) - HTML 5 Canvas library (a flash alternative) written in Coffeescript
* [stevejackson/mazery](https://github.com/stevejackson/mazery) - Maze generation visualizer using html5 Canvas, Coffeescript, jQuery, Compass
* [mconintet/brownie](https://github.com/mconintet/brownie) - A canvas toolkit in coffeescript

### Game Development

* [soulwire/Coffee-Physics](https://github.com/soulwire/Coffee-Physics) - A simple, lightweight physics engine written in CoffeeScript
* [swarmsim/swarm](https://github.com/swarmsim/swarm) - Swarm Simulator, an idle game with lots of bugs.
* [maddox/kart](https://github.com/maddox/kart) - 🎮 Frontend for RetroArch
* [stephank/orona](https://github.com/stephank/orona) - Bolo, a game of tank warfare, rewritten for modern browsers. *(archived)*
* [iiegor/slither](https://github.com/iiegor/slither) - An open source implementation of the slither.io server
* [Retronator/Pixel-Art-Academy](https://github.com/Retronator/Pixel-Art-Academy) - An adventure game for learning to draw.
* [mycard/srvpro](https://github.com/mycard/srvpro) - A server for YGOPro
* [alexmoon/ksp](https://github.com/alexmoon/ksp) - Kerbal Space Program Mission Plotter *(archived)*
* [hyspace/flappy](https://github.com/hyspace/flappy) - flappy bird in html5
* [flynngao/FlappyTube](https://github.com/flynngao/FlappyTube) - Crazy H5 Game which Tube kill birds
* [plehoux/fontBomb](https://github.com/plehoux/fontBomb) - An html 5 experiment where you can destroy any webpage with bombs!
* [neotenic/protobowl](https://github.com/neotenic/protobowl) - real time multiplayer quizbowl
* [jacobwgillespie/heroku-minecraft](https://github.com/jacobwgillespie/heroku-minecraft) - :gem: run a Minecraft server on Heroku
* [nornagon/atom](https://github.com/nornagon/atom) - a <canvas> game framework that does as little as possible
* [uhyo/jinrou](https://github.com/uhyo/jinrou) - Are you a werewolf?
* [mdp/MachinePoker](https://github.com/mdp/MachinePoker) - Gambling.js
* [schibo/1964js](https://github.com/schibo/1964js) - Nintendo64 emulator in JavaScript
* [rachel-carvalho/voxel-mars](https://github.com/rachel-carvalho/voxel-mars) - Global-scale reproduction of Mars on voxel.js
* [stephank/villain](https://github.com/stephank/villain) - Real-time browser games in JavaScript and CoffeeScript. *(archived)*
* [jamesmoriarty/nebula](https://github.com/jamesmoriarty/nebula) - WebGL top down space shooter. *(archived)*
* [john-griffin/gibdo](https://github.com/john-griffin/gibdo) - HTML5 Canvas 2D Engine in CoffeeScript
* [LanJian/coffee2d](https://github.com/LanJian/coffee2d) - A HTML5 2D game engine written in CoffeeScript
* [perrysmotors/framer-physics](https://github.com/perrysmotors/framer-physics) - A module for adding 2D physics simulations to your Framer prototypes.
* [chrissharkey/pong](https://github.com/chrissharkey/pong) - HTML5 Canvas Pong game in Coffeescript

### Audio

* [audiocogs/aurora.js](https://github.com/audiocogs/aurora.js) - JavaScript audio decoding framework
* [BaiduMusic/muplayer](https://github.com/BaiduMusic/muplayer) - An open source web audio player from Baidu Music, support HTML5 and Flash engine on different platforms(百度音乐播放内核)
* [audiocogs/alac.js](https://github.com/audiocogs/alac.js) - ALAC decoder, but in Coffeescript
* [podigee/podigee-podcast-player](https://github.com/podigee/podigee-podcast-player) - Podcast Web Player
* [webcast/webcaster](https://github.com/webcast/webcaster) - Client for the webcast websocket protocol.
* [benjamindenboer/Framer-AudioPlayer](https://github.com/benjamindenboer/Framer-AudioPlayer) - AudioPlayer Module for Framer. See the new, Design-compatible Audio module here: https://github.com/benjamindenboer/FramerAudio
* [wit-ai/microphone](https://github.com/wit-ai/microphone) - Microphone in the browser using WebRTC and WebSockets *(archived)*
* [crispymtn/crispyfi](https://github.com/crispymtn/crispyfi) - Makes music. Loud. https://www.crispymtn.com/stories/let-the-music-play *(archived)*
* [alpacaaa/max4node](https://github.com/alpacaaa/max4node) - Control Ableton Live through Node.js. Yes, holy shit.
* [1j01/wavey](https://github.com/1j01/wavey) - An HTML5 online audio editor (BUGGY and not in development)
* [rorhug/ng-drum](https://github.com/rorhug/ng-drum) - AngularJS drum machine
* [halfbyte/liv3c0der](https://github.com/halfbyte/liv3c0der) - liv3c0der lives! see halfbyte/liv3c0der-mk2 *(archived)*
* [bjjb/chromaprint.js](https://github.com/bjjb/chromaprint.js) - A JavaScript implementation of AcoustID Chromaprint
* [0xfe/fretboard](https://github.com/0xfe/fretboard) - Vex Fretboard as seen on my.vexflow.com.
* [arximboldi/mixco](https://github.com/arximboldi/mixco) - Mixco is a framework for creating hardware controller scripts for the amazing Mixxx DJ software

### Image and Video

* [jariz/vibrant.js](https://github.com/jariz/vibrant.js) - Extract prominent colors from an image. JS port of Android's Palette. *(archived)*
* [meltingice/psd.js](https://github.com/meltingice/psd.js) - A Photoshop PSD file parser for NodeJS and browsers
* [iizukanao/node-rtsp-rtmp-server](https://github.com/iizukanao/node-rtsp-rtmp-server) - RTSP/RTMP/HTTP hybrid server
* [amw/jpeg_camera](https://github.com/amw/jpeg_camera) - JpegCamera – JavaScript webcam image capture library
* [endlesshack/youtube-video](https://github.com/endlesshack/youtube-video) - A Javascript library to access webm, mp4 sources for Youtube Videos.
* [trello-archive/iconathon](https://github.com/trello-archive/iconathon) - An icon task runner that convert Sketch files to mobile and web formats.
* [meltingice/CamanJS-Plugins](https://github.com/meltingice/CamanJS-Plugins) - Plugins for CamanJS, a Javascript image manipulation library
* [lukasklein/itunes-colors](https://github.com/lukasklein/itunes-colors) - Porting Panic's iTunes album art color algortithm (http://www.panic.com/blog/2012/12/itunes-11-and-colors/) to JavaScript
* [tanaikech/ImgApp](https://github.com/tanaikech/ImgApp) - A powerful image processing library for Google Apps Script (GAS) to retrieve image size/DPI via binary parsing, resize images, update thumbnails, crop/merge images, and perform OCR using Google Drive API v3.
* [jembezmamy/morpher-js](https://github.com/jembezmamy/morpher-js) - JavaScript image morphing library
* [Intervox/node-webp](https://github.com/Intervox/node-webp) - node.js wrapper for cwebp and dwebp binaries from WebP image processing utility
* [Rafe/papercut](https://github.com/Rafe/papercut) - node module to resize and crop image
* [elchiapp/foscam_streamer](https://github.com/elchiapp/foscam_streamer) - A small tool to stream Foscam IP cameras on the web
* [applest/node-applest-atem](https://github.com/applest/node-applest-atem) - A module to control Blackmagic Design ATEM Switchers
* [Lepozepo/cloudinary](https://github.com/Lepozepo/cloudinary)
* [gazs/canvas-atkinson-dither](https://github.com/gazs/canvas-atkinson-dither)
* [OiNutter/Obscura](https://github.com/OiNutter/Obscura) - Canvas Based Image Manipulation Library
* [dcollien/Dreamcoat](https://github.com/dcollien/Dreamcoat) - Formerly "AutoScheme". Automatically generates a website colour scheme from a given logo image. Written in literate coffeescript.

## Security

### Cryptography

* [keybase/node-client](https://github.com/keybase/node-client) - CLI for keybase.io written in/for Node.js *(archived)*
* [joegoldbeck/mongoose-encryption](https://github.com/joegoldbeck/mongoose-encryption) - Simple encryption and authentication plugin for Mongoose
* [keybase/proofs](https://github.com/keybase/proofs) - Public Keybase Proof System
* [ChristopherA/revocable-self-signed-tls-certificates-hack](https://github.com/ChristopherA/revocable-self-signed-tls-certificates-hack) - As a proof-of-concept, we will show how easy it is to revoke a self-signed certificate using the bitcoin blockchain. This will also demonstrate how we may be able to use similar approaches for more advanced capabilities that current X.509 infrastructure do not.
* [alax/jsrp](https://github.com/alax/jsrp) - JavaScript implementation of the Secure Remote Password protocol

### Security Tools

* [dropbox/zxcvbn](https://github.com/dropbox/zxcvbn) - Low-Budget Password Strength Estimation
* [rastapasta/pokemon-go-mitm](https://github.com/rastapasta/pokemon-go-mitm) - 🎁 Pokemon Go MITM Proxy - Intercepts the traffic between your Pokemon Go app and their servers, decodes the protocol and gives you a handy tool to enrich your own game experience on the fly. *(archived)*
* [mozilla/seasponge](https://github.com/mozilla/seasponge) - :pineapple: SeaSponge is an accessible threat modelling tool from Mozilla *(archived)*
* [futpib/policeman](https://github.com/futpib/policeman) - Firefox extention for cross-site requests control (kind of RequestPolicy clone) *(archived)*
* [bermanto/mitm-omegle](https://github.com/bermanto/mitm-omegle) - Watch strangers talk on Omegle (man in the middle attack explained for kids)
* [trailbot/client](https://github.com/trailbot/client) - Trailbot tracks files and logs in your servers and triggers Smart Policies upon unwanted modification.
* [BoLaMN/tch-exploit](https://github.com/BoLaMN/tch-exploit) - Technicolor OpenWRT Shell Unlocker
* [feross/CMSploit](https://github.com/feross/CMSploit) - Security scanner to find temporary config files that contain passwords on public websites *(archived)*
* [hmarr/chromesheep](https://github.com/hmarr/chromesheep) - FireSheep for Chrome *(archived)*

### Authentication and Authorization

* [lynndylanhurley/ng-token-auth](https://github.com/lynndylanhurley/ng-token-auth) - Token based authentication module for angular.js.
* [oauth-io/oauth-js](https://github.com/oauth-io/oauth-js) - OAuth that just works ! This is the JavaScript SDK for OAuth.io
* [Clever/saml2](https://github.com/Clever/saml2) - Node module to abstract away the complexities of the SAML protocol behind an easy to use interface.
* [anvilresearch/connect](https://github.com/anvilresearch/connect) - A modern authorization server built to authenticate your users and protect your APIs *(archived)*
* [Differential/accounts-entry](https://github.com/Differential/accounts-entry) - Meteor sign up and sign in pages
* [domenic/restify-oauth2](https://github.com/domenic/restify-oauth2) - A simple OAuth 2 endpoint for Restify
* [hubot-archive/hubot-auth](https://github.com/hubot-archive/hubot-auth) - Assign roles to users and restrict command access in other scripts
* [twilio/authy-form-helpers](https://github.com/twilio/authy-form-helpers) - Authy javascripts and css file to help create quick forms for the authy api *(archived)*

## Concurrency and Performance

### Concurrency and Parallelism

* [goodeggs/fibrous](https://github.com/goodeggs/fibrous) - Easily mix asynchronous and synchronous programming styles in node.js.
* [sudhirj/simply-deferred](https://github.com/sudhirj/simply-deferred) - A deferred library for Node.js and the browser with a jQuery compatible API
* [Flipboard/express-cluster](https://github.com/Flipboard/express-cluster)
* [tanaikech/RunAll](https://github.com/tanaikech/RunAll) - This is a library for running the concurrent processing using only native Google Apps Script (GAS).
* [ramesaliyev/EasyWebWorker](https://github.com/ramesaliyev/EasyWebWorker) - Easy Communication Protocol For Web Workers
* [setthase/division](https://github.com/setthase/division) - Simple yet powerful wrapper over node.js cluster API.
* [jprichardson/node-nextflow](https://github.com/jprichardson/node-nextflow) - A simple control-flow library for Node.js targetted towards CoffeeScript developers.

## Testing and Quality

### Testing

* [mojotech/pioneer](https://github.com/mojotech/pioneer) - Integration Testing
* [trello-archive/scientist](https://github.com/trello-archive/scientist) - A Node.js library for carefully refactoring critical paths in production
* [cybertk/abao](https://github.com/cybertk/abao) - REST API automated testing tool based on RAML
* [joshbuddy/ghostbuster](https://github.com/joshbuddy/ghostbuster) - Integration testing ftw
* [karma-runner/karma-ng-html2js-preprocessor](https://github.com/karma-runner/karma-ng-html2js-preprocessor) - A Karma plugin. Compile AngularJS 1.x and 2.x templates to JavaScript on the fly. *(archived)*
* [winsonwq/viff](https://github.com/winsonwq/viff) - Viff Testing Framework. Find visual differences between web pages in different environments(developing, staging, production) and browsers.
* [searls/jasmine-given](https://github.com/searls/jasmine-given) - Like rspec-given, but for jasmine
* [benbria/coffee-coverage](https://github.com/benbria/coffee-coverage) - Istanbul and JSCoverage-style instrumentation for CoffeeScript files.
* [quangv/mocha-cakes](https://github.com/quangv/mocha-cakes) - (inactive) BDD mocha test framework add-on, stories with Cucumber style Given/When/Then syntax for Node.js
* [goodeggs/chai-webdriver](https://github.com/goodeggs/chai-webdriver) - Build more expressive integration tests with webdriver sugar for chai.js
* [vojtajina/node-mocks](https://github.com/vojtajina/node-mocks) - Suite of mocks for node.js (fs, http) + some testing utils...
* [mtsmfm/hubot-test-helper](https://github.com/mtsmfm/hubot-test-helper) - Helper for testing hubot script
* [chaijs/chai-things](https://github.com/chaijs/chai-things) - Chai support for assertions on array elements
* [billtrik/karma-fixture](https://github.com/billtrik/karma-fixture) - A plugin for the Karma test runner that loads .html and .json fixtures
* [brianmhunt/casper-chai](https://github.com/brianmhunt/casper-chai) - Extends Chai with assertions for the CasperJS/PhantomJS headless browser.
* [bwiklund/jray](https://github.com/bwiklund/jray) - realtime javascript code coverage
* [karma-runner/karma-html2js-preprocessor](https://github.com/karma-runner/karma-html2js-preprocessor) - A Karma plugin. Convert HTML files into JS strings to serve them in a script tag. *(archived)*
* [abe33/spectacular](https://github.com/abe33/spectacular) - Advanced BDD framework for CoffeeScript and JavaScript
* [xdissent/karma-browserify](https://github.com/xdissent/karma-browserify) - [deprecated] Browserify for Karma
* [fcoury/atom-rspec](https://github.com/fcoury/atom-rspec) - Atom RSpec runner package
* [jmreidy/vows-bdd](https://github.com/jmreidy/vows-bdd) - A BDD wrapper for Vows, allowing for easy writing of tests in a given-when-then format

## Utilities

### Command Line Tools

* [sgentle/caniuse-cmd](https://github.com/sgentle/caniuse-cmd) - Caniuse command line tool
* [f/omelette](https://github.com/f/omelette) - Omelette is a simple, template based autocompletion tool for Node and Deno projects with super easy API. (For Bash, Zsh and Fish)
* [iostreamer-X/Awkward](https://github.com/iostreamer-X/Awkward) - A NodeJS based shell. Everything is an Object!
* [nkohari/jwalk](https://github.com/nkohari/jwalk) - command-line json inspector
* [xdissent/iectrl](https://github.com/xdissent/iectrl) - Command line interface and Node module for managing ievms virtual machines
* [unix/fine.sh-cli](https://github.com/unix/fine.sh-cli) - generate your static website in 3 seconds *(archived)*
* [adaltas/node-parameters](https://github.com/adaltas/node-parameters) - Nice looking shell applications with pluggable middlewares for Node.js
* [docopt/docopt.coffee](https://github.com/docopt/docopt.coffee) - docopt - A command line option parser that will make you smile.
* [KyleAMathews/facebook-export](https://github.com/KyleAMathews/facebook-export) - Tools to help administer your Facebook groups
* [paulyoung/fontello-cli](https://github.com/paulyoung/fontello-cli) - Command line interface for fontello.
* [markbrown4/egghead-downloader](https://github.com/markbrown4/egghead-downloader) - downloads egghead
* [quackingduck/wach](https://github.com/quackingduck/wach) - Run a command when a file add/update event occurs
* [tebriel/jira-cli](https://github.com/tebriel/jira-cli) - Simple Command Line Jira Client in Node.js *(archived)*
* [stephenb/node-notes](https://github.com/stephenb/node-notes) - A node.js version of Rails' "rake notes" functionality
* [assaf/sideline](https://github.com/assaf/sideline) - Sideline, a CoffeeScript shell for your server (NO LONGER MAINTAINED) *(archived)*
* [jimmycuadra/bang](https://github.com/jimmycuadra/bang) - Text snippets on the command line.
* [dmotz/soundscrape](https://github.com/dmotz/soundscrape) - SoundCloud command line downloader in Node.js

### Text Processing

* [sstephenson/eco](https://github.com/sstephenson/eco) - Embedded CoffeeScript templates *(archived)*
* [mauricemach/coffeekup](https://github.com/mauricemach/coffeekup) - Markup as CoffeeScript.
* [andreyvit/json-diff](https://github.com/andreyvit/json-diff) - Structural diff for JSON files
* [dodo/node-slug](https://github.com/dodo/node-slug) - slugifies even utf-8 chars!
* [elving/swag](https://github.com/elving/swag) - Swag is a growing collection of helpers for handlebars templates.
* [snd/url-pattern](https://github.com/snd/url-pattern) - easier than regex string matching patterns for urls and other strings. turn strings into data or data into strings.
* [nevir/groc](https://github.com/nevir/groc) - Documentation generation, in the spirit of literate programming.
* [cyrilis/epub-gen](https://github.com/cyrilis/epub-gen) - Generate EPUB books from HTML with simple API in Node.js.
* [segmentfault/HyperDown.js](https://github.com/segmentfault/HyperDown.js)
* [STRd6/jadelet](https://github.com/STRd6/jadelet) - Pure and simple clientside templates
* [github/task_list](https://github.com/github/task_list) - GitHub flavor Markdown Task List feature components *(archived)*
* [stripe-archive/jquery.mobilePhoneNumber](https://github.com/stripe-archive/jquery.mobilePhoneNumber) - [DEPRECATED] A general purpose library for validating and formatting mobile phone numbers. *(archived)*
* [beautiful-docs/beautiful-docs](https://github.com/beautiful-docs/beautiful-docs) - A beautiful way to read documentation *(archived)*
* [arnab/jQuery.PrettyTextDiff](https://github.com/arnab/jQuery.PrettyTextDiff) - A wrapper around Google's diff_match_patch library, to make life easy
* [openbibleinfo/Bible-Passage-Reference-Parser](https://github.com/openbibleinfo/Bible-Passage-Reference-Parser) - Typescript to identify and understand Bible references like "John 3:16."
* [qiao/difflib.js](https://github.com/qiao/difflib.js) - Text diff library in JavaScript, ported from Python's difflib module.
* [jotux/fangle](https://github.com/jotux/fangle) - fangle creates interactive pages from plain text
* [gradus/coffeecup](https://github.com/gradus/coffeecup) - keeping the project alive with this clone of mauricemach/coffeekup
* [pvande/Milk](https://github.com/pvande/Milk) - Milk is Mustache in CoffeeScript -- great with your browser or NodeJS!
* [malgorithms/toffee](https://github.com/malgorithms/toffee) - a NodeJS and browser templating language based on coffeescript, with the slickest syntax ever
* [jessegrosjean/birch-outline](https://github.com/jessegrosjean/birch-outline) - Cross-platform scripting for TaskPaper
* [duncanbeevers/jade-react](https://github.com/duncanbeevers/jade-react) - Compile Jade templates to React.DOM expressions
* [vol4ok/hogan-express](https://github.com/vol4ok/hogan-express) - Mustache template engine for express 3.x. Support partials and layout
* [mbrevoort/docco-husky](https://github.com/mbrevoort/docco-husky) - A fork of docco for generating documentation for a whole project
* [goodeggs/teacup](https://github.com/goodeggs/teacup) - Teacup is templates in CoffeeScript
* [uglyog/clientside-haml-js](https://github.com/uglyog/clientside-haml-js) - Haml compiler for client side javascript view templates
* [mohebifar/angular-persian](https://github.com/mohebifar/angular-persian) - :earth_asia: Persian tools for angular.js
* [cstivers78/bliss](https://github.com/cstivers78/bliss) - Template Engine for Node.js, inspired by .NET Razor and Play! Scala Templates
* [softwarerero/meteor-accounts-t9n](https://github.com/softwarerero/meteor-accounts-t9n) - Translations for meteor account's error messages
* [danxexe/sms-counter](https://github.com/danxexe/sms-counter) - Character counter for SMS messages.
* [notslang/instagram-id-to-url-segment](https://github.com/notslang/instagram-id-to-url-segment) - Convert Instagram post IDs into Instagram links, algorithmically
* [lever/planer](https://github.com/lever/planer) - Remove reply quotations from emails
* [notslang/tidy-markdown](https://github.com/notslang/tidy-markdown) - Beautify Markdown, fixing formatting mistakes and standardizing syntax
* [dylandy/tobopomo.js](https://github.com/dylandy/tobopomo.js) - A simple and easy plugin for convert string to Bopomo script and Chinese Characters.
* [nok/markdown-toc](https://github.com/nok/markdown-toc) - Generate and update magically a table of contents based on the headlines of a parsed markdown file. *(archived)*
* [4vanger/angular-l10n](https://github.com/4vanger/angular-l10n) - L10n module for Angular.js
* [mroth/emoji-data-js](https://github.com/mroth/emoji-data-js) - :sunglasses: Emoji encoding swiss army knife for NodeJS *(archived)*
* [notduncansmith/animal-namer](https://github.com/notduncansmith/animal-namer) - Generate alliterative animal usernames
* [roddeh/i18njs](https://github.com/roddeh/i18njs) - Internationalisation library for JS projects
* [alecperkins/active-markdown](https://github.com/alecperkins/active-markdown) - A tool for creating Markdown-sourced reactive documents. Literate CoffeeScript meets Tangle.
* [mikesmullin/coffee-templates](https://github.com/mikesmullin/coffee-templates) - Fastest Minimalist CoffeeScript/JavaScript CoffeeCup/Handlebars/Mustache template engine.
* [grncdr/uri-template](https://github.com/grncdr/uri-template) - TypeScript/Javascript implementation of RFC 6570 for URI-templates
* [jimmycuadra/shellwords](https://github.com/jimmycuadra/shellwords) - Manipulate strings according to the word parsing rules of the UNIX Bourne shell.
* [andreaspitzer/parse-decimal-number](https://github.com/andreaspitzer/parse-decimal-number) - 🏧 Parse a decimal number with i18n format support (localized decimal points and comma separators)
* [rferro/normat](https://github.com/rferro/normat) - Generic javascript number/string formatting (bytes, milliseconds, ...).
* [zerobase/enml2md](https://github.com/zerobase/enml2md) - Evernote to Markdown Converter
* [jaekwon/CoffeeMugg](https://github.com/jaekwon/CoffeeMugg) - HTML templates in pure CoffeeScript
* [devongovett/spellchecker.js](https://github.com/devongovett/spellchecker.js) - A spellchecker in CoffeeScript/JavaScript based on Hunspell

### Date and Time

* [icambron/twix.js](https://github.com/icambron/twix.js) - :hourglass::left_right_arrow: A date range plugin for moment.js
* [myrne/performance-now](https://github.com/myrne/performance-now) - Implements performance.now (based on process.hrtime).
* [icambron/moment-countdown](https://github.com/icambron/moment-countdown) - Use Countdown.js from Moment.js
* [hijonathan/moment.twitter](https://github.com/hijonathan/moment.twitter) - A Twitter-like date formatter for moment.js
* [OutlawAndy/relativeDate](https://github.com/OutlawAndy/relativeDate) - Angular.js service providing auto-updating, relative time labels like "about 1 minute ago"
* [davidchambers/an.hour.ago](https://github.com/davidchambers/an.hour.ago) - A small utility which enables wonderfully expressive date and time manipulation in JavaScript
* [imakewebthings/timeline](https://github.com/imakewebthings/timeline) - A generic event timeline for node.js or the browser. Written in CoffeeScript.

### Automation and Scripting

* [github/hubot-scripts](https://github.com/github/hubot-scripts) - DEPRECATED, see https://github.com/github/hubot-scripts/issues/1113 for details - optional scripts for hubot, opt in via hubot-scripts.json *(archived)*
* [slackapi/hubot-slack](https://github.com/slackapi/hubot-slack) - Slack Developer Kit for Hubot *(archived)*
* [phonowell/genshin-impact-script](https://github.com/phonowell/genshin-impact-script) - 原神脚本，包含自动钓鱼、自动拾取、自动跳过对话等多项实用功能。A Genshin Impact script includes many useful features such as automatic fishing, automatic item pickup, automatic dialogue skipping, etc.
* [xhan/qqbot](https://github.com/xhan/qqbot) - 基于WebQQ协议的QQ机器人。命令行工具，Hubot支持！
* [hipchat/hubot-hipchat](https://github.com/hipchat/hubot-hipchat) - HipChat adapter for GitHub's Hubot
* [minefold/hubot-minecraft](https://github.com/minefold/hubot-minecraft) - A Minecraft hubot adapter *(archived)*
* [nandub/hubot-irc](https://github.com/nandub/hubot-irc) - IRC adapter for Hubot
* [paulmillr/top-github-users](https://github.com/paulmillr/top-github-users) - GitHub top-1000 generation script
* [SerjoPepper/bot-brother](https://github.com/SerjoPepper/bot-brother) - Node.js framework for telegram bots
* [miyagawa/hubot-cron](https://github.com/miyagawa/hubot-cron) - Crontab like scheduling messages for Hubot
* [hubot-archive/hubot-heroku-keepalive](https://github.com/hubot-archive/hubot-heroku-keepalive) - A hubot script that keeps the hubot Heroko web dyno alive
* [xmppjs/hubot-xmpp](https://github.com/xmppjs/hubot-xmpp) - XMPP adapter for Hubot
* [digitalocean/heartbot](https://github.com/digitalocean/heartbot) - A shot of love for your favorite chat client.
* [clabot/clabot](https://github.com/clabot/clabot) - A bot to take the pain out of Contributor License Agreements *(archived)*
* [stephenyeargin/hubot-grafana](https://github.com/stephenyeargin/hubot-grafana) - 📈🤖 Query Grafana dashboards
* [RocketChat/hubot-natural](https://github.com/RocketChat/hubot-natural) - Natural Language Processing Chatbot for RocketChat *(archived)*
* [netpro2k/hubot-skype](https://github.com/netpro2k/hubot-skype) - Skype adapter for hubot
* [hubot-archive/hubot-google-images](https://github.com/hubot-archive/hubot-google-images) - A hubot script that interacts with the Google Images API
* [microsoft/BotFramework-Hubot](https://github.com/microsoft/BotFramework-Hubot) - Hubot adapter for botframework *(archived)*
* [hubot-archive/hubot-business-cat](https://github.com/hubot-archive/hubot-business-cat) - Business cat is summoned when business jargon is used
* [smblott-github/chromix-too](https://github.com/smblott-github/chromix-too) - External access to Chrome's internal Javascript API.
* [iangreenleaf/githubot](https://github.com/iangreenleaf/githubot) - Github API access, tailored for Hubot
* [bearyinnovative/hubot-bearychat](https://github.com/bearyinnovative/hubot-bearychat) - BearyChat Adapter for Hubot
* [flowdock/hubot-flowdock](https://github.com/flowdock/hubot-flowdock) - Flowdock adapter for Hubot chat bot *(archived)*
* [miyagawa/hubot-standup](https://github.com/miyagawa/hubot-standup) - Agile style standup bot with hubot, ala tender
* [naoya/hubot-sushiyuki](https://github.com/naoya/hubot-sushiyuki)
* [samlambert/hubot-mysql-chatops](https://github.com/samlambert/hubot-mysql-chatops) - ChatOps for MySQL.
* [sdslabs/jinora](https://github.com/sdslabs/jinora) - Slack webhook app to create anonymous public channels
* [chen-ye/hubot-fb](https://github.com/chen-ye/hubot-fb) - A Hubot adapter for the Facebook Messenger Platform
* [MathildeLemee/hubot-twitter](https://github.com/MathildeLemee/hubot-twitter) - Twitter adapter for Hubot
* [ssokolow/itad_importer](https://github.com/ssokolow/itad_importer) - A userscript helper for importing game collections into IsThereAnyDeal.com
* [rikukissa/domo](https://github.com/rikukissa/domo) - Domo the incredible irc-bot
* [bhuga/hubot-chatops-rpc](https://github.com/bhuga/hubot-chatops-rpc) - Register servers to provide chatops over a simple HTTP protocol
* [thetimpanist/hubot-discord](https://github.com/thetimpanist/hubot-discord) - Hubot adapter for Discord
* [huafu/hubot-gitter2](https://github.com/huafu/hubot-gitter2) - Hubot adapter for Gitter
* [saschagehlich/hotnode](https://github.com/saschagehlich/hotnode) - Hot code loading for node.js
* [renanvicente/hubot-mattermost](https://github.com/renanvicente/hubot-mattermost) - A hubot adapter for Mattermost
* [sakatam/hubot-reviewer-lotto](https://github.com/sakatam/hubot-reviewer-lotto) - A reviewer lottery script for Hubot
* [akiomik/hubot-chatwork](https://github.com/akiomik/hubot-chatwork) - A hubot adapter for chatwork
* [idobata/hubot-idobata](https://github.com/idobata/hubot-idobata) - Idobata adapter for GitHub's Hubot
* [DamageLabs/hubot-kandan-app](https://github.com/DamageLabs/hubot-kandan-app) - An easily deployed Hubot for Kandan, running in the cloud.
* [yoheimuta/hubot-aws](https://github.com/yoheimuta/hubot-aws) - Hubot masters aws commands
* [smashwilson/hubot-markov](https://github.com/smashwilson/hubot-markov) - Hubot watches all, and builds a markov model from everything you say.
* [hubot-archive/hubot-github-repo-event-notifier](https://github.com/hubot-archive/hubot-github-repo-event-notifier) - Notifies about any GitHub repo event available via webhook.
* [matsukaz/hubot-schedule](https://github.com/matsukaz/hubot-schedule) - A hubot script to schedule a message in both cron-style and datetime-based format pattern
* [seblavoie/adobe-illustrator-layer-renamer](https://github.com/seblavoie/adobe-illustrator-layer-renamer) - Adobe Illustrator script to batch rename layers.
* [danielbayley/alfred-finder-new-item](https://github.com/danielbayley/alfred-finder-new-item) - Swiftly create new items in Finder with support for templates.
* [rsm-hcd/hubot-jenkins-enhanced](https://github.com/rsm-hcd/hubot-jenkins-enhanced) - Jenkins integration for Hubot with multiple server support *(archived)*
* [hassaku/hubot-suggest](https://github.com/hassaku/hubot-suggest) - Suggest hubot commands when not found
* [hubot-archive/hubot-darksky](https://github.com/hubot-archive/hubot-darksky) - A script to grab the forecast information from Dark Sky for Hubot
* [hubot-archive/hubot-seen](https://github.com/hubot-archive/hubot-seen) - A hubot script that tracks when/where users were last seen.
* [wildownes/CryptoCoffeeBot](https://github.com/wildownes/CryptoCoffeeBot) - Coffeescript base skeleton code that can be used to fork into useful bots for cryptotrader.org

### General Purpose Libraries

* [hasclass/core-lib](https://github.com/hasclass/core-lib) - A port of the Ruby 1.9.3 corelib to coffeescript/javascript/node that conforms to rubyspec.org. *(archived)*
* [vojtajina/node-di](https://github.com/vojtajina/node-di) - Dependency Injection framework for Node.js
* [florrain/locale](https://github.com/florrain/locale) - Browser locale negotiation for node.js
* [adamhooper/js-priority-queue](https://github.com/adamhooper/js-priority-queue) - Priority queues in JavaScript
* [raganwald/YouAreDaChef](https://github.com/raganwald/YouAreDaChef) - Coffeescript/Javascript method combinations for Underscore projects
* [kendagriff/workflow.js](https://github.com/kendagriff/workflow.js) - JS-based Finite State Machine for Backbone.js
* [raganwald/Katy](https://github.com/raganwald/Katy) - CoffeeScript and JavaScript Combinators
* [jrus/chromatist](https://github.com/jrus/chromatist) - A JavaScript library for working with colors and color spaces
* [qiao/heap.js](https://github.com/qiao/heap.js) - A binary heap implementation in CoffeeScript/JavaScript.
* [raganwald/method-combinators](https://github.com/raganwald/method-combinators)
* [davidgtonge/underscore-query](https://github.com/davidgtonge/underscore-query) - MongoDB like query api for JavaScript Arrays
* [elclanrs/essential.js](https://github.com/elclanrs/essential.js) - Essential JS - Functional JavaScript "the right way"
* [HubSpot/mixen](https://github.com/HubSpot/mixen) - Combine Javascript classes on the fly
* [kmalakoff/mixin](https://github.com/kmalakoff/mixin) - Mixin.js is the 'reuse more' Javascript nano-framework. Stay DRY...mixin!
* [yocontra/node-linq](https://github.com/yocontra/node-linq) - LINQ for node
* [chainyjs/chainy](https://github.com/chainyjs/chainy) - The chainy core + autoloader plugin
* [linus/senseunit](https://github.com/linus/senseunit) - Unit conversion in the browser
* [domenic/dict](https://github.com/domenic/dict) - A lightweight but safe dictionary, for when Object won't cut it
* [Kikobeats/array-future](https://github.com/Kikobeats/array-future) - Proposed Array prototype helpers and polyfills exploring future ECMAScript collection APIs.
* [dodo/node-bufferstream](https://github.com/dodo/node-bufferstream) - painless stream buffering, cutting and piping
* [mgeraci/Coffee-Filter](https://github.com/mgeraci/Coffee-Filter) - A collection of coffeescript helpers that I've used across projects
* [Qix-/node-error-ex](https://github.com/Qix-/node-error-ex) - Easy error subclassing and stack customization
* [baconjs/bacon.model](https://github.com/baconjs/bacon.model) - Model plugin for bacon.js
* [atom/theorist](https://github.com/atom/theorist) - A reactive model toolkit for CoffeeScript *(archived)*
* [elbywan/quadtree-lib](https://github.com/elbywan/quadtree-lib) - Efficient quadtrees library written in CoffeeScript.
* [shinout/interval-tree2](https://github.com/shinout/interval-tree2) - interval tree in CoffeeScript, available in any JS runtime
* [nogizhopaboroda/f_context](https://github.com/nogizhopaboroda/f_context) - Pattern matching and easy recursion library for CoffeeScript
* [stephenb/coffee-machine](https://github.com/stephenb/coffee-machine) - A state machine written in CoffeeScript.
* [STRd6/priority_queue](https://github.com/STRd6/priority_queue) - A JavaScript PriorityQueue
* [MichaelBlume/coffeestream](https://github.com/MichaelBlume/coffeestream) - streams in coffeescript
* [rubyjs/core-lib](https://github.com/rubyjs/core-lib) - A port of the Ruby 1.9.3 corelib to coffeescript/javascript/node that conforms to rubyspec.org. *(archived)*

## Business and Domain

### Finance and Trading

* [stripe-archive/jquery.payment](https://github.com/stripe-archive/jquery.payment) - [DEPRECATED] A general purpose library for building credit card forms, validating inputs and formatting numbers. *(archived)*
* [buttercoin/buttercoin](https://github.com/buttercoin/buttercoin) - Opensource Bitcoin Exchange Software
* [discolabs/cartjs](https://github.com/discolabs/cartjs) - A Javascript library to power cart management for Shopify themes.
* [jondavidjohn/payform](https://github.com/jondavidjohn/payform) - :credit_card: A library for building credit card forms, validating inputs, and formatting numbers.
* [halloffame/ynab-csv](https://github.com/halloffame/ynab-csv) - Tool for making your CSV files ready to import into YNAB
* [pcrawfor/iap_verifier](https://github.com/pcrawfor/iap_verifier) - Node.js implementation of iOS In App Purchase receipt verification
* [vtex/vtex.js](https://github.com/vtex/vtex.js) - VTEX SDK for JavaScript
* [alanhoff/node-pagseguro](https://github.com/alanhoff/node-pagseguro) - Integração ao Pagseguro para sistemas usando o Node.js
* [doomhz/coinnext](https://github.com/doomhz/coinnext) - Crypto currency exchange - Bitcoin to altcoins
* [akalankauk/ValidMYCard-Credit-Card-Generator-Validiator](https://github.com/akalankauk/ValidMYCard-Credit-Card-Generator-Validiator) - Simple Credit Card Generator & Validiator |Based on HTML,Javascript,Jquery |

### Business and Productivity

* [taigaio/taiga-front](https://github.com/taigaio/taiga-front)
* [manuel-schoebel/ms-seo](https://github.com/manuel-schoebel/ms-seo) - A seo helper package for meteor.js
* [slaypni/SM-15](https://github.com/slaypni/SM-15) - Spaced repetition for memorizing tons of things.
* [omsmith/ims-lti](https://github.com/omsmith/ims-lti) - A node.js library implementing the IMS LTI tool providers' standards
* [rockymadden/gap](https://github.com/rockymadden/gap) - :nut_and_bolt: Fix default Google Analytics tracking methodologies and track micro user behaviors. *(archived)*

## Science and Math

### Scientific Computing

* [sagemathinc/cocalc](https://github.com/sagemathinc/cocalc) - CoCalc: Collaborative Calculation in the Cloud *(archived)*
* [daraosn/oculus-drone](https://github.com/daraosn/oculus-drone) - Oculus Rift + AR Drone 2.0 controller with live video feed and head-motion controller.
* [kbroman/qtlcharts](https://github.com/kbroman/qtlcharts) - R/qtlcharts: An R package for interactive QTL graphics
* [NetLogo/Galapagos](https://github.com/NetLogo/Galapagos) - NetLogo model simulation visualizer (Beak) and the netlogoweb.org website 🐢
* [raganwald/cafeaulife](https://github.com/raganwald/cafeaulife) - Gosper’s HashLife in CoffeeScript

## Other

* [dansinker/tacofancy](https://github.com/dansinker/tacofancy) - community-driven taco repo. stars stars stars.
* [boennemann/badges](https://github.com/boennemann/badges) - :flower_playing_cards: Readme Badges – Gotta catch 'em all
* [rs/pushd](https://github.com/rs/pushd) - Blazing fast multi-protocol mobile and web push notification service
* [jaymedavis/hubble](https://github.com/jaymedavis/hubble) - A dashboard that displays in the terminal
* [davidedc/Algebrite](https://github.com/davidedc/Algebrite) - Computer Algebra System in Javascript (Typescript)
* [octoblu/meshblu](https://github.com/octoblu/meshblu) - Meshblu is a cross-protocol IoT machine-to-machine messaging system.
* [weixiyen/messenger.js](https://github.com/weixiyen/messenger.js) - Insanely Fast Communication Library For Node.js Services
* [agentvps/codo](https://github.com/agentvps/codo) - agentvps
* [pimatic/pimatic](https://github.com/pimatic/pimatic) - A home automation server and framework for the raspberry pi running on node.js
* [osuushi/Smooth.js](https://github.com/osuushi/Smooth.js) - Turn arrays into smooth functions.
* [lucagrulla/node-tail](https://github.com/lucagrulla/node-tail) - The zero dependency Node.js module for tailing a file
* [ottypes/json0](https://github.com/ottypes/json0) - Version 0 of the JSON OT type
* [jrcryer/grunt-pagespeed](https://github.com/jrcryer/grunt-pagespeed) - Grunt plugin to run Google PageSpeed Insights as part of CI
* [netzpirat/openclaw-trading-agent](https://github.com/netzpirat/openclaw-trading-agent) - trading agent
* [grahamjenson/ger](https://github.com/grahamjenson/ger) - Good Enough Recommendation (GER) Engine
* [fluuuid/codedoodl.es](https://github.com/fluuuid/codedoodl.es) - A curated showcase of creative coding sketches
* [idealclover/Love-Gift](https://github.com/idealclover/Love-Gift) - 💌 A love gift for my ex-girlfriend. *(archived)*
* [atom/fuzzaldrin](https://github.com/atom/fuzzaldrin) - Fuzzy filtering and string scoring *(archived)*
* [ricardobeat/filr](https://github.com/ricardobeat/filr) - Store files in your Flickr account
* [jeancroy/fuzz-aldrin-plus](https://github.com/jeancroy/fuzz-aldrin-plus) - Sublime text like fuzzy filtering - compatible with atom/fuzzaldrin
* [crispymtn/linear-partition](https://github.com/crispymtn/linear-partition) - Linear partition in Coffeescript (Javascript)
* [latentflip/violin](https://github.com/latentflip/violin) - Violin
* [microflo/microflo](https://github.com/microflo/microflo) - Live dataflow programming for microcontrollers and embedded
* [axiomzen/Alike](https://github.com/axiomzen/Alike) - A simple-but-useful kNN library for NodeJS, comparing JSON Objects using Euclidean distances
* [omarkhan/coffeedoc](https://github.com/omarkhan/coffeedoc) - An API documentation generator for CoffeeScript
* [grahamjenson/hapiger](https://github.com/grahamjenson/hapiger) - HapiGer is an http-wrapper around the Good Enough Recommendation engine using the Hapi.js framework
* [AriaMinaei/RenderKid](https://github.com/AriaMinaei/RenderKid) - Stylish console.log for node
* [sagivo/accept-bitcoin](https://github.com/sagivo/accept-bitcoin) - Accept bitcoin payments using Node.js
* [stephenlacy/movel](https://github.com/stephenlacy/movel) - Móvel - Dashboard for Raspberry pi car computer
* [carrot/ship](https://github.com/carrot/ship) - ⛔️ currently unmaintained ⛔️
* [Ysheep666/starry](https://github.com/Ysheep666/starry) - starry.so 完成一个故事
* [technoweenie/nubnub](https://github.com/technoweenie/nubnub) - Node.js PubSubHubbub client/server implementation
* [msgflo/msgflo](https://github.com/msgflo/msgflo) - Distributed Flow-Based Programming via message queues
* [shesek/bitrated](https://github.com/shesek/bitrated) - Bitrated v1
* [homebrewing/brauhausjs](https://github.com/homebrewing/brauhausjs) - A beer recipe calculator for homebrewing on servers and in browsers
* [websecurify/node-vortex](https://github.com/websecurify/node-vortex) - *(archived)*
* [stephan83/babar](https://github.com/stephan83/babar) - CLI bar charts for node.js
* [hstove/electron-cookies](https://github.com/hstove/electron-cookies) - Adds support for cookies in Electron. Cookies are persisted through localStorage.
* [tapquo/atoms](https://github.com/tapquo/atoms) - Atomic development
* [atom/fs-plus](https://github.com/atom/fs-plus) - node's fs module with some helpful additions *(archived)*
* [nashby/jose-vs-oss](https://github.com/nashby/jose-vs-oss) - I'm here to help @josevalim fight Gihub issues
* [gjtorikian/biscotto](https://github.com/gjtorikian/biscotto) - UNMAINTAINED. CoffeeScript API documentation tool that uses TomDoc notation. *(archived)*
* [qeda/qeda](https://github.com/qeda/qeda) - The tool for easy creating electronic component libraries
* [torontojs/torontojs.com](https://github.com/torontojs/torontojs.com) - The Website for TorontoJS
* [lancejpollard/mint.js](https://github.com/lancejpollard/mint.js) - NO LONGER SUPPORTED
* [axiomzen/Look-Alike](https://github.com/axiomzen/Look-Alike) - A simple-yet-powerful KD-tree library for NodeJS, with support for lightning-fast k-Nearest Neighbour queries.
* [bertelsmannstift/GED-VIZ](https://github.com/bertelsmannstift/GED-VIZ)
* [vlandham/bubble_cloud](https://github.com/vlandham/bubble_cloud)
* [cognitom/tokoro](https://github.com/cognitom/tokoro) - 住所緯度経度変換ライブラリ (ジオコーディング)
* [HabitRPG/habitrpg-shared](https://github.com/HabitRPG/habitrpg-shared) - Shared resources useful for multiple HabitRPG repositories. Assets (sprites, imgs, etc), CSS, algorithms, and more.
* [atom/node-pathwatcher](https://github.com/atom/node-pathwatcher) - Path Watcher Node Module *(archived)*
* [fukayatsu/esarea](https://github.com/fukayatsu/esarea) - Enjoy (\( ⁰⊖⁰)/) markdown!
* [itsthatguy/gridwax](https://github.com/itsthatguy/gridwax)
* [technoweenie/node-chain-gang](https://github.com/technoweenie/node-chain-gang)
* [flyingmachine/gratefulplace2](https://github.com/flyingmachine/gratefulplace2)
* [polvo/polvo](https://github.com/polvo/polvo) - Polyvalent cephalopod mollusc.
* [sgentle/chip](https://github.com/sgentle/chip)
* [atom/atomdoc](https://github.com/atom/atomdoc) - Atom's documentation parser for JavaScript / CoffeeScript *(archived)*
* [andrzejsliwa/coffeeapp](https://github.com/andrzejsliwa/coffeeapp) - not needed any more, couchdb is handling of coffeescript natively https://github.com/bdionne/couchdb/commit/972da5ab71af3eaeb939314a973398b6fe3235a9
* [yusugomori/deeplearning.coffee](https://github.com/yusugomori/deeplearning.coffee) - Simple JavaScript (CoffeeScript) codes implementing deep learning
* [alfrednerstu/fractional-design](https://github.com/alfrednerstu/fractional-design) - Fractional design leadership for mobile apps and web platforms. Embedded in your team, guiding strategy and execution from concept to launch.
* [STRd6/zine](https://github.com/STRd6/zine) - DIY E-Zine and Operating System
* [Marak/xp](https://github.com/Marak/xp) - agile programming tools in Coffeescript
* [lynaghk/cassowary-coffee](https://github.com/lynaghk/cassowary-coffee) - CoffeeScript port of the Cassowary linear constraint solver
* [coffee-js/index.coffee-js.org](https://github.com/coffee-js/index.coffee-js.org) - CoffeeScript 中文资源
* [croquiscom/crojsdoc](https://github.com/croquiscom/crojsdoc) - A documentation generator for JavaScript and CoffeeScript *(archived)*
* [toshok/coffeekit](https://github.com/toshok/coffeekit) - CoffeeScript bindings for OSX and IOS apis
