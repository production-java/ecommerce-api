# EcommerceApi Currently in production

## This project will have information about different types of backend servers for example aws azure or google, just generic information about costs etc etc. Currently I'm also working on a computer angular site, such site users will have the ability to search different laptops and buy them. However, this repo is simply a snapshot of the configuration of main ts , index html, decorators , component ts , bootstrap and cli configurations, along with some important logistics to keep in mind before working with the framework. Thanks for reading!

Before diving into the dark with ferocity and begin the angular app, there is some vocabulary that should be learned in order to understand the many components living insde the framework. For this process lets break down the strucutre into chunks.

Component & Databinding: Important features about apps are build from components and databinding is simply how you output data in the DOM (document object model).

Directives: NG model in a two-way data binding is a directive , you can build your own directives. Sorta of little helpers or instruction you can place in html code which will then do something at runtime depending on the commands.

Services/Dependency Injection: The core features of angular which makes it easy for different pieces in the app to communicate with each other and have a centralized code and manage the state of the application.

Routing: This makes the user think we are switching pages even though technically, we still remain on a single page. Routing shows how it works.

Observables: It is a concept allowing to work with asynnchronous code and angular embraces it.

Forms: Handling user input is a key task on any application.

Pipes: This feature makes it easy to transform the output (what you display on the template at runtime).

HTTP: What if we need to reach a webserver? What if you need to store some data in a database? Angular can’t connect to a database directly but it can connect to a server. (MEAN STACK) IN ACTION.

Authentication: In simple words if you are on netflix with a simple membership you can only view 1 HD quality video at a time BUT ,if you have a premium account you can view 3 HD quality videos a the same time in other words the preferred registered member aka authenticated user is able to enjoy the perk of a premium account.

Optimization & NgModules: We can manage different modules in the application.

Deployment: How to deploy from local machine using docker or aws or heroku.

Animation & Testing: ….. well at this point once the app is complete we will move on to the next part and dive into testing utilizing open source technologies. 🙂

 
currently in development….

MVC

bootstrap

js

ts

directives

json configuation

potentially docker ,aws s3 or heroku.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
