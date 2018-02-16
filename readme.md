# What is it about (Conceptual View)?

Riffs-n-Genre enables Architecture-as-Code for Microservices DevOps Pipelines through the following features:
- Riffs which are definitions of various software and infrastructure building blocks using an  Architecture-Domain-Specific-Language (ADSL) for Microservices Applications
- Genres which are templates of various software and infrastructure artifacts (code, diagrams, documentation) for various implementation-specific DevOps patterns (e.g. 'persistence-via-mongodb')
- Strings which generate artifacts by merging Riffs and Genres
- Streams which transport artifacts to various DevOps Pipeline repositories

## How does it work (Functional View)?
- Riffs are defined using JSON. The ADSL is defined using JSON Schema.
- Genres are defined using [mustache template syntax](https://mustache.github.io/mustache.5.html)
- Strings is a nodejs program that choreographs artifact generation using [mustache.js](https://github.com/janl/mustache.js/) and git repo interaction using [nodegit](https://github.com/nodegit/nodegit)
- Streams is a python program that orchestrates AWS Code Pipeline interaciton using [AWS CLI](https://github.com/aws/aws-cli)

# How is the code organized (Development View)?
*still work in progress...*

# How is the code built (Build View)?
*still work in progres...*

## How to install (Deployment View)?
*still work in progress...*

## How to run (Operational View)?
*stil work in progress...*
