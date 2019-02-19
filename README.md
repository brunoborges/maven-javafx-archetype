# maven-openjfx-archetype

A Maven Archetype for OpenJFX (JavaFX) starter projects. For more information, visit [OpenJFX.io](https://openjfx.io). The code sample in this project is based on the [HelloFX example](https://github.com/openjfx/samples/tree/6226973589d905a77326c0391ac3fbbc4ca7d3cc/HelloFX/Maven).

[![Build Status](https://dev.azure.com/brunoborges-github/maven-openjfx-archetype/_apis/build/status/brunoborges.maven-openjfx-archetype?branchName=master&label=Build)](https://dev.azure.com/brunoborges-github/maven-openjfx-archetype/_build/latest?definitionId=2&branchName=master)

## Requirements

- Maven 3 (or later)
- OpenJDK 11 (or later)

## Create a project

Run the following command:

```
mvn archetype:generate                                  \
  -DarchetypeGroupId=io.brunoborges                     \
  -DarchetypeArtifactId=maven-openjfx-archetype         \
  -DarchetypeVersion=11.0.2-SNAPSHOT
```

## Run the project

Go into the project folder, and run:

    mvn package exec:java
