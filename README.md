# Vert.x Cassandra client

[![Build Status](https://travis-ci.org/vert-x3/vertx-cassandra-client.svg?branch=initial-work)](https://travis-ci.org/Sammers21/vertx-cassandra-client)

The Vert.x Cassandra client is an extension for interacting with [Apache Cassandra](http://cassandra.apache.org/).

The client is built on top of [DataStax Java Driver](https://github.com/datastax/java-driver).

## Building the client

In order to build the client, run this:

```bash
git clone https://github.com/vert-x3/vertx-cassandra-client
cd vertx-cassandra-client
mvn clean install -Dmaven.test.skip=true -s .travis.maven.settings.xml 
```

Note: You need to have java 8 for building the client.


## Docs
After the building, documentation can be found in the **target/asciidoc** directory.
