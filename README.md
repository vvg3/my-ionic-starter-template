# my-ionic-starter-template
starter template for an ionic project

This project includes the following installations:
  - karma | to facilitate testing in browsers
  - karma-cli | to interact with karma via the terminal
  - karma-chrome-launcher | to launch the karma window in Chrome, Chrome Canary or Chromium
  - karma-jasmine | a karma adapter for the Jasmine testing framework
  - karma-mocha-reporter | a karma plugin for reporting in the terminal with mocha style logging
  - karma-remap-istanbul | allows the reports being watched to be remapped and measured for coverage with Istanbul 
  - angular | a command line interface for Angular
  - codecov | to measure source code executed by a test suite
  - jasmine-core | testing framework for JavaScript
  - jasmine-spec-reporter | to print test results to the console in real time
  - @types/jasmine | package containing type definitions for Jasmine
  - ts-node | TypeScript execution environment for node
  - @types/node | package containing type definitions for Node
  - tslint | an extensible static analysis tool that checks TypeScript code for errors
  - tslint-eslint-rules | adds the missing ESLint rules

This project adds to the blank ionic template:
  - karma.conf.js | to configure Karma (https://karma-runner.github.io/0.13/config/configuration-file.html)
  - angular-cli.json | to configure Angular CLI
  - src/environments/environment | dev environment
  - src/environments/environment.prod | prod environment
  - src/mocks | simplified classes used for testing
  - src/polyfills | needed by Angular 2 and is loaded before the app