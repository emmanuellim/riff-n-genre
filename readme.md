# What is it about (Conceptual View)?

Riffs-n-Genre enables Architecture-as-Code and Continuous Architecture Integration through the following features
- `Riffs` are Architecture Building Blocks that are coded using an Architecture-Domain-Specific Language (ADSL)
- `Genres` are templates for Architecture artifacts (e.g. UML diagramms, decisions, interface contracts) 
- `Jams` generate artifacts by merging Riffs and Genres
- `Ensembles` are Continuous Integration Pipelines that validate the cohesion of Architecture Building Blocks of a solution 

## How does it work (Functional View)?
- `Riffs` are defined using JSON. The ADSL is defined using JSON Schema.
- `Genres` are defined using [mustache template syntax](https://mustache.github.io/mustache.5.html)
- `Jams` is a nodejs program that choreographs artifact generation using [mustache.js](https://github.com/janl/mustache.js/) and git repo interaction using [nodegit](https://github.com/nodegit/nodegit)
- `Ensembles` is a python program that orchestrates AWS Code Pipeline interaction using [AWS CLI](https://github.com/aws/aws-cli)

# How is the code organized (Development View)?
*still work in progress...*

# How is the code built (Build View)?
*still work in progres...*

## How to install (Deployment View)?
*still work in progress...*

## How to run (Operational View)?
*stil work in progress...*
