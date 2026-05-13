# Mark59 Parent POM

Welcome to the Mark59 Parent POM documentation.

## Overview

**Mark59 Parent POM** is a parent POM for Mark59 Java projects.

- **Group ID**: `mark59-parent-pom`
- **Artifact ID**: `mark59-parent-pom`
- **Current Version**: `5.6.3.00`

## Adding to Your Project

To use this parent POM in your Maven project, add the following to your `pom.xml`:

```xml
<parent>
    <groupId>mark59-parent-pom</groupId>
    <artifactId>mark59-parent-pom</artifactId>
    <version>5.6.3.00</version>
</parent>
```

## Project Configuration

### Java Version
- **Target**: Java 17
- **Source**: Java 17
- **Encoding**: UTF-8

### Dependencies

The parent POM includes managed dependencies for:

- **Logging**: Apache Log4j 2.25.4
- **JMeter**: 5.6.3
- **Mark59**: 6.5
- **Apache Batik**: 1.17 (SVG rendering)
- **XStream**: 1.4.21 (XML serialization)
- **DataFaker**: 2.5.4

### Build Plugins

The parent POM includes:

- **Maven Compiler Plugin** (3.10.1) - Java compilation
- **Maven JAR Plugin** (3.2.2) - JAR packaging with manifest
- **Maven Dependency Plugin** (3.3.0) - Dependency management during build

## Repository

For more information and to contribute, visit the [Mark59 Parent POM repository](https://github.com/mark59pom/parent-pom).
