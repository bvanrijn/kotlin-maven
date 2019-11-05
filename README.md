# kotlin-maven

Set up a project that uses Kotlin and Maven to target the JVM.

It's based on [Maven in 5 Minutes](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html) and
[Using Maven with Kotlin](https://kotlinlang.org/docs/reference/using-maven.html).

## Setup

First, click <a href="https://github.com/bvanrijn/kotlin-maven/generate"><img src=images/use-this-template.png alt="the Use this template button" height="16" /></a> and create a repository from that screen.

Then update `pom.xml` to change the name, group ID, artifact ID, et cetera, and update the `src/main` and `src/test`
directory layout to match.

## Usage

```bash
# Run tests and create a JAR
mvn package
# Run it
java -cp target/kotlin-maven-1.0-SNAPSHOT-jar-with-dependencies.jar com.mycompany.app.App
```
