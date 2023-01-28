# scala-web-maven-spring-jsp-ssl-postgres-simple

## Description
A POC for springboot web app with jsp support
connecting to a self-signed ssl enabled postgres database.

## Tech stack
- scala
- maven
  - springboot
  - jsp
  - postgres connector
- bootstrap
- jquery
- dataTable

## Docker stack
- alpine
- postgres
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
Available at http://localhost

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://spring.io/guides/gs/accessing-data-mysql/
- https://medium.com/@gustavo.ponce.ch/spring-boot-jquery-datatables-a2e816e2b5e9
