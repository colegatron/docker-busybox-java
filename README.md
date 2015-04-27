## Minimal Docker image with Java [![Build Status](https://travis-ci.org/jeanblanchard/docker-busybox-java.svg?branch=master)](https://travis-ci.org/jeanblanchard/docker-busybox-java)

# Better use the Dockerfile in conjuntion with https://github.com/gliderlabs/docker-alpine
###It has a wider package repository to be used as base but the Jean script is still necesary for java install.



Basic [Docker](https://www.docker.com/) image to run [Java](https://www.java.com/) applications.
This is based off [Busybox](http://www.busybox.net/) to keep the size minimal (about 25% of an ubuntu-based image).

### Tags

* `latest` or `8`: Oracle Java 8 (Server JRE)
* `7`: Oracle Java 7 (Server JRE)
* `jdk8`: Oracle Java 8 (JDK)
* `jdk7`: Oracle Java 7 (JDK)

### Usage

Example: 

    docker run -it --rm jeanblanchard/busybox-java:8 java -version
