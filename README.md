# Portal-Build

Parent build file for the Portal creation, assumes you have Aache Maven installed in your local development environment.
### Usage.

Clone the project using GIT client into an empty folder and use the below command to clean install the dependencies one by one. This folder will be the parent folder, where one needs to clone dependent projects. 
```
mvn clean install
```
### Dependent Modules

Ensure that module requirements are meet before starting build (see build file for more details). ( e.g.: Database local instance, user credentials for connecting to database ) as this step is mandatory for success full build of portal.
