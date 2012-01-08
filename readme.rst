=========
JPetStore
=========

This is a copy of Springs JPetStore sample application, taken from https://src.springframework.org/svn/spring-samples/jpetstore/trunk/org.springframework.samples.jpetstore. See original-readme.txt.

The intention is to use this as a basis for trying out different web technologies.

So far:

- Fixed versions in pom.xmls in order to make the application build
- Added dependencies to SLF4J
- Added Jetty

To run:

- mvn clean install
- db/hsqldb/server.sh
- mvn jetty:run
- Go to localhost:8080
