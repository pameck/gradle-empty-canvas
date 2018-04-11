# Empty Gradle Canvas

An empty Gradle project template.

Perfect for quick projects, coding workshops or as the basis for something bigger.

## What's included

* [Gradle](https://gradle.org/) as a build tool
* [JUnit](https://junit.org/junit4/) for unit tests
* An `EmptyCanvas` class with a method returning a String
* A passing tests which asserts the String returned.

## Quick setup

```shell
$ git clone git@github.com:pameck/gradle-empty-canvas.git
$ cd gradle-empty-canvas
$ ./gradlew check

BUILD SUCCESSFUL in 2s
3 actionable tasks: 3 executed
```

### IntelliJ Setup

1. Import Project
1. Import project from external model
1. Next, next, next, Finish... you know the drill.


## Usage

### Building the application

`./gradlew build`

### Running the tests

`./gradlew check`

Or, to run the tests once and then automatically re-run them when the code changes:

`./gradlew --continuous check`
