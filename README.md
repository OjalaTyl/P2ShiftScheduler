# Shift Scheduler

## Project Description
Shift Scheduler provides a streamlined solution for managers to create shift schedules instead of manual scheduling. Managers can create shift schedules and provides a centralized network for communication within the company, as well as be notified of shifts, conflicts, and changes. Users can post their availability or request time off within a period of time that has been set by their manager.

## Technologies Used

- JavaSe - version 1.8
- Spring AOP, MVC, and Orm - version 5.2.12
- Jackson - version 2.11.3
- Hibernate - version 5.4.10
- Postgresql - version 42.2.18
- JUnit - version 4.12

## Features

List of features ready and TODOs for future development

- Viewing completed schedules
- Assistance in creating schedules
- Creating and viewing bulletin messages from managers
- Messaging between employees
- Setting own availability

To-do list:

- Logging through Log4j utilizing aspects

## Getting Started

run git clone https://github.com/OjalaTyl/P2ShiftScheduler.git

Import the back-end into the java ide of your choice then be sure everything is working by using a Maven update.
Open the front end folder in Visual Studio Code. Next open an angular cli in the project folder and run cli install to download all dependencies.
If you do not have tomcat installed you will need to install version 9.0. Go to tomcat's website for further information.

## Usage

# P2RESTonSpring

Locate the application context file and replace the Amazon RDS info with the info that you use.
Next run the application and select the tomcat server that you have installed

If you want to connect to the server via postman the endpoints will be on http://localhost:8080/P2Scheduler/[

# P2RESTonAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.5.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
