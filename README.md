# groovy-cli-gradle-postgresql-data-type-json

## Description
Creates a small table `dog` that uses
a json data type.

A groovy gradle build, that connects to postgresql database.

## Tech stack
- groovy
- gradle
  - log4j
  - postgresql drivers

## Docker stack
- postgresql:alpine
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[JSON data type info](https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-json/)
