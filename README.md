# jSwatch - Swatch Internet Time converter in Java

# EXAMPLE

```console
$ gradle shadowJar
$ bin/swatch
@105.32
```

# REQUIREMENTS

* [JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html) 1.7+
* [gradle](http://gradle.org/) 2.1+

## Optional

* [Sonar](http://www.sonarqube.org/)
* [Infer](http://fbinfer.com/)
* [Ruby](https://www.ruby-lang.org/en/) 2.7+
* [Python](https://www.python.org/) 3+

# JAVADOCS

```console
$ gradle javadoc
$ open build/docs/javadoc/index.html
```

# TEST + CODE COVERAGE

```console
$ gradle test jacoco
$ open build/reports/jacoco/test/html/index.html
```

# LINTING

```console
$ gradle check
```

## Optional: FindBugs

```console
$ gradle check
$ open build/reports/findbugs/main.html
```

## Optional: Sonar

```console
$ sonar start
$ gradle check sonar
$ open http://localhost:9000/
```

## Optional: Infer

```console
$ infer -- gradle clean build
```
