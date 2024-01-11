# Establishing the Architectural Style in both Container Diagrams.

## Context and Problem Statement

I need to be able to choose the correct Architecture Style 

## Considered Options

* Service Oriented Architecture
* Microservice Architecture

## Decision Outcome

 I have chosen " Microservice Architecture "
* Its very scalable, and can be useful when needing to expand different services
* Great for security; usage of API Gateway
* Splitting front end and back end services

## Consequences

* Good, because it accurately depics the users interaction with the system
* Bad, because it increases the complexity of the system as compared to SOA
* Bad, performance can decrease due to latency issues and communication between services.

## Pros and Cons of the Options

### Service Oriented Architecture
* Has great reusability
* Also has great replaceability of services without affecting the system as a whole


