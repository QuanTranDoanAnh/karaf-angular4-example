# Building Angular 4 Web Bundle for Apache Karaf

Following the tutorial at link: http://blog.nanthrax.net/?p=827 with simple CRUD added.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.
Then a pom.xml is added to turn it into a Web Bundle for Karaf.

## Try the example code

1. Run `mvn clean install` to get Angular CLI to generate deployable source code and to have Maven to package it into Karaf-compatible bundle. 
2. From Karaf console, run `install mvn:vn.quantda/test-frontend/1.0-SNAPSHOT` to deploy the web bundle to Karaf.
3. Open browser, browse to http://localhost:8181/angular-test/ to enjoy the web app.
