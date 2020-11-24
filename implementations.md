# Implementations

## Server Implementations:

* [GOST](#GOST)
* [FROST-Server](#FROST)
* [52°North STA](#52°North STA)

### GOST

GOST is an open source implementation of the SensorThings API in the Go programming language initiated by Geodan. It contains easily deployable server software and a JavaScript client. Currently (June 2016) it is in development but a first version can already be downloaded and deployed. The software can be installed on any device supporting Docker or Go (e.g. Windows, Linux, Mac OS and Raspberry Pi). By default sensor data is stored in a PostgreSQL database. 

Repository - https://github.com/gost/server 

### FROST

FROST-Server is an Open Source server implementation of the OGC SensorThings API. FROST-Server implements the entire specification, including all extensions. It is written in Java and can run in Tomcat or Wildfly and is available as a Docker image. Among its many features is the ability to use String or UUID based entity IDs. 

Repository - https://github.com/FraunhoferIOSB/FROST-Server

### 52°North STA

52N SensorThingsAPI is an open source implementation of the OGC SensorThings API. Its core features are the interoperability with the (52°North SOS)[https://github.com/52North/sos] implementing the (OGC Sensor Observation Service)[https://www.ogc.org/standards/sos], customizable database mappings and several convenience extensions. It can be deployed as a Docker container, inside an Apache Tomcat or as a standalone application. 

Repository - https://github.com/52North/sensorweb-server-sta

# Client Implementations:

* [FROST-Client](#FROST-Client)
* [Grafana LinkSmart SensorThings plugin]()

### Frost-Client

FROST-Client is a Java client library for communicating with a SensorThings API compatible server. 

Repository - https://github.com/FraunhoferIOSB/FROST-Client

### Grafana LinkSmart SensorThings plugin

The SensorThings plugin for (Grafana)[https://grafana.com/] is a simple library for visualising SensorThingsAPI data inside a Grafana Dashboard.

Official website - https://grafana.com/grafana/plugins/linksmart-sensorthings-datasource

Repository - https://github.com/linksmart/grafana-sensorthings-datasource
