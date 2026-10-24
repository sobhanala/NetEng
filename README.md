# NetEng — Java Project Starter

A Maven-based Java project with the artifact name `meowbook`. The current repository contains an entry point at `src/main/java/org/example/Main.java` and a minimal Maven configuration.

## Requirements

- JDK 21, matching the compiler settings in `pom.xml`.
- Maven.

## Build

```sh
mvn package
java -cp target/classes org.example.Main
```

The current entry point prints `Hello world!`. This snapshot does not declare external dependencies in its Maven configuration.
