# kotlin-maven

Set up a project that uses Kotlin and Maven to target the JVM.

It's based on [Maven in 5 Minutes](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html) and
[Using Maven with Kotlin](https://kotlinlang.org/docs/reference/using-maven.html).

## Setup

First clone the repository and change to it:

```bash
git clone --depth 1 https://github.com/bvanrijn/kotlin-maven
cd kotlin-maven
```

Then, remove the `.git` directory (and optionally, `.github`, too, if you don't want to use GitHub Actions):

```bash
rm -rf .git
```

Then update `pom.xml` to change the name, group ID, artifact ID, et cetera, and update the `src/main` and `src/test`
directory layout to match.

## Usage

```bash
# Run tests and create a JAR
mvn package
# Run it
java -cp target/kotlin-maven-1.0-SNAPSHOT-jar-with-dependencies.jar com.mycompany.app.App
```