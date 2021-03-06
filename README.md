This project is an example how to use [jBPM3](http://www.jboss.org/jbpm).

To run it you'll need:

* [Apache Maven](http://maven.apache.org/download.html "Apache Maven")
* [Eclipse](http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/indigor Eclipse) or [IntelliJ Idea](http://www.jetbrains.com/idea/download/index.html "IntelliJ Idea")

Install apache maven, then run in command line:

```
$ mkdir repo
$ cd repo
$ git clone git@github.com:aeremenok/jbpm-examples.git

$ cd jbpm-examples
; the following will download library dependencies from maven repository
$ mvn clean compile
; the following will create an eclipse config from the existing maven config (pom.xml)
$ mvn eclipse:eclipse
```

Then import the existing project into Eclipse.

The project also uses [TestNG](http://testng.org/doc/index.html "TestNG") to implement unit-tests and [SLF4J](http://www.slf4j.org/ "SLF4J") for logging.

The examples of usage are located in test classes like src/test/java/edu/leti/jbpm/SuccessfulProcessTest.java
