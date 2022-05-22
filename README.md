# XDTesting Setup Environment

This action enables you to set up a stable environment for running test cases for ontology testing based on the [eXtreme Design](extremedesign.info) ontology modelling methodology. It prepares an environment by firstly setting up Java Temurin 17 and then downloading the latest version of [OWLUnit](https://github.com/luigi-asprino/owl-unit/releases/tag/0.3.2) jar which has been developed to run unit tests for ontologies defined according to the [OWLUnit Ontology](https://w3id.org/OWLunit/ontology/).

# Usage 
Add the following entry to your Github workflow YAML file:

```
steps:
  - name: XDTesting Setup Environment
    uses: FiorelaCiroku/XDTesting-SetupEnvironment@v1.0.0
```
