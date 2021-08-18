# Kotlin library archetype
Maven archetype to generate a kotlin library project with a Spring Boot example app.

## How to run
* Install the archetype locally with `mvn install`.
* Generate project with:
```shell
mvn archetype:generate                                  \
  -DarchetypeGroupId=nl.ict-jv                          \
  -DarchetypeArtifactId=kotlin-library-archetype        \
  -DarchetypeVersion=0.1.0                              
```