# java-web-gradle-spring-thyme-sqlserver-ssl-simple

## Description
A thyme springboot java gradle build,
that connects to sqlserver database.

Sql server uses self-signed ssl.

## Tech stack
- springboot
  - web
- thymeleaf
- gradle
  - 6.8.2
- bootstrap
- jquery
- dataTable

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- gradle:jdk11

## To run
`sudo ./install.sh -u`
Available http://localhost

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
