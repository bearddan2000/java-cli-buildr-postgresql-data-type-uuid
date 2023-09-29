# java-cli-buildr-postgresql-data-type-uuid

## Description
Creates a small table `dog` that uses
a uuid data type.

A java buildr build, that connects to postgresql database.

## Tech stack
- java
- buildr
  - log4j
  - postgresql drivers

## Docker stack
- postgresql:alpine
- vanto/apache-buildr:latest-jruby-jdk8

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
