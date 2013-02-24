# Basic Auth-Filter-Extension for Neo4j-Server

Just put the jar-file into `plugins` and add the following lines to the `conf/neo4j-server.properties` file. 
The username:password combination are the admin credentials, please change as appropriate.

    org.neo4j.server.credentials=username:password
    org.neo4j.server.thirdparty_jaxrs_classes=org.neo4j.server.extension.auth=/auth

