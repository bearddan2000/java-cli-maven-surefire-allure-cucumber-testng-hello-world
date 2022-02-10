# java-cli-maven-surefire-allure-cucumber-testng-hello-world

## Description
A POC for maven app using testNg
and cucumber framework with allure,
and surefire plugins.

Serves allure report from link given
after the build.

## Tech stack
- java
- maven
  - testNg
  - surefire
  - cucumber
	- allure

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Jacoco config](https://www.baeldung.com/jacoco)
