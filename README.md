# task-flow

## Tech stack
* React - frontend
* Node.js - package manager and build tool for frontend
* Java - backed
* Spring boot - backend framework
* MySQL - database

## Pre-requisite
* Node v20.13.1
* Java v17 (JDK)

## How to build and run locally
### How to build ###
```bash
# 1. Install dependencies in frontend
$ cd frontend
$ npm install

# 2. Add necessary dependencies to backend's pom.xml
$ cd backend
## Add required libraries to the pom.xml file for your Java backend
## For example, Spring Boot, database drivers, or other necessary dependencies
```

### How to run locally ###
```bash
# 1. run frontend
$ cd frontend
$ npm run dev

# 2. run backend
$ cd backend
$ mvn spring-boot:run
```