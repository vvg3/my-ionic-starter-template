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
  - src/environments/environment.ts | dev environment
  - src/environments/environment.prod.ts | prod environment
  - src/mocks.ts | simplified classes used for testing
  - src/polyfills.ts | needed by Angular 2 and is loaded before the app
  - src/test.ts | test file
  - src/tsconfig.test.json | test configuration

This project edits:
  - package.json | to add a scripts "test" object
  - karma.conf.js | change angular-cli to @angular/cli (frameworks, require and preprocessors)
  - package.json | zone.js version 8.24
  - angular-cli.json | to remove "source" from environments and add "environmentSource" element