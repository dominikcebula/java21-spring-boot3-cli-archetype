# Java 21 Spring Boot 3 CLI Archetype

## Intro

This repository contains a Maven Archetype that can be used to generate a Java 21 Spring Boot 3 CLI project.

Included example code will create a Spring Boot 3 CLI Application:
```
  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v3.0.2)

...

Hello World!
```

## Usage

Invoke command:
```
mvn archetype:generate -DarchetypeGroupId=com.dominikcebula.archetypes -DarchetypeArtifactId=java21-spring-boot3-cli-archetype
```

Maven Archetype will ask about `groupId`, `artifactId`, `version`, `package name` and will generate a project skeleton.

## Generated project

Having the project generated, invoke:
```
mvn clean install
```

Executable jar with all dependencies will be generated under `target` folder.

You can execute generated `jar` using command:
```
java -jar target/generated-output-1.0-SNAPSHOT.jar
```
