# jSwatch - Swatch Internet Time converter in Java

# EXAMPLE

```
$ gradle shadowJar
$ bin/swatch
@105.32
```

# REQUIREMENTS

* [JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html) 1.7+
* [Gradle](http://gradle.org/) 2.1+

## Optional

* [Sonar](http://www.sonarqube.org/)

E.g., `brew install gradle sonar sonar-runner`

# JAVADOCS

```
$ gradle javadoc
$ open build/docs/javadoc/index.html
```

# TEST + CODE COVERAGE

```
$ gradle test jacoco
$ open build/reports/jacoco/test/html/index.html
```

# LINTING

```
$ gradle check
```

## Optional: Sonar

```
$ sonar start
$ gradle check sonar
$ open http://localhost:9000/
```
