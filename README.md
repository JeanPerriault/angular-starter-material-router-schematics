# Angular Starter - Material, router and schematics


## Live demo
TODO


## How to build that

### Install npm and nodejs

$ npm update -g

$ npm -v
6.4.1

$ node -v
v8.11.1

$ npm ls --depth=0 -g
$ npm i -g @angular/cli

$ ng new starter

$ cd starter

$ ng add @angular/material

Not enough, so add:
$ npm i --save @angular/cdk @angular/animations

Add "import { BrowserAnimationsModule } from '@angular/platform-browser/animations';" in app.module.ts

$ vi angular.json


$ ng generate @angular/material:material-nav --name navigation

$ ng generate @angular/material:material-dashboard --name dashboard
$ ng generate component stepper
$ ng generate component expansion-panel

Update navigation links in navigation components, routes in app.module.ts, update components with your content

$ ng serve
$ ng serve --prod

$ ng build
$ ng build --prod

And you're done!
Thx Angular Teams contributors
Thx Github Teams and contributors
Thx all ninja coders on stackoverflow and dev blogs



## Additional notes (default README from Angular CLI)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.1.

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


