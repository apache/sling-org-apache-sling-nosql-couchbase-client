[<img src="https://sling.apache.org/res/logos/sling.png"/>](https://sling.apache.org)

 [![Build Status](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-nosql-couchbase-client/job/master/badge/icon)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-nosql-couchbase-client/job/master/) [![Test Status](https://img.shields.io/jenkins/tests.svg?jobUrl=https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-nosql-couchbase-client/job/master/)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-nosql-couchbase-client/job/master/test/?width=800&height=600) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-nosql-couchbase-client&metric=coverage)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-nosql-couchbase-client) [![Sonarcloud Status](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-nosql-couchbase-client&metric=alert_status)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-nosql-couchbase-client) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.sling/org.apache.sling.nosql.couchbase-client/badge.svg)](https://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.apache.sling%22%20a%3A%22org.apache.sling.nosql.couchbase-client%22) [![JavaDocs](https://www.javadoc.io/badge/org.apache.sling/org.apache.sling.nosql.couchbase-client.svg)](https://www.javadoc.io/doc/org.apache.sling/org.apache.sling.nosql.couchbase-client) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![nosql](https://sling.apache.org/badges/group-nosql.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/groups/nosql.md)&#32;[![contrib](https://sling.apache.org/badges/status-contrib.svg)](https://github.com/apache/sling-aggregator/blob/master/docs/status/contrib.md)

# Apache Sling NoSQL Couchbase Client

This module is part of the [Apache Sling](https://sling.apache.org) project.

Provides preconfigured clients for accessing a [Couchbase](http://www.couchbase.com/) NoSQL database.

* Wraps the [Couchbase Java Client 2.x](https://github.com/couchbase/couchbase-java-client) and exports it via OSGi
* Includes private dependencies of Couchbase Java Client
* The couchbase access parameters can be configured via OSGi configuration.
* Multiple couchbase clients can be configured for different couchbase hosts and/or buckets
