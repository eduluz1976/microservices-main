# Microservices

This document describes the main requirements, assumptions, constraints and implementations details of different implementations of a set of projects.


# Projects


## Hello World

### Introduction

This microservice is a basic implementation of a REST API provider. 

### Requirements

#### Routes

The following routes should be implemented:

- GET /status
- GET /helloWorld
- GET /

#### Infrastructure

- All implementations should be deployed in a Docker image. 
- Should have a common container, responsible for integration tests. This container receives as environment variables the URL + port of the service, and performs the tests.
- The solution should be stateless, ensuring high scalability.

- Would be great to have the option to enable registration in a Consul instance. 



### Implementations

#### Raw PHP

#### Phalcon

#### Laravel

#### NodeJS

#### Java (Spring)


