# ADempiere Meta Project
Tool to build and install all artifacts of ADempiere project including vue client ad grpc server. 
In future project will allow to install many instances of ADempiere and provide systemctl config.
Initial focus is to install ADempiere on up to date servers (JBoss Wildfly and most recent Tomcat)
as well as have alternative ADempiere build scripts which can build with new versions of Java
to have ability to develop with up to date tools.

The basic idea is to have shadow ADemepire with new features which can be later integrated into
production

## Build
``` bash
./gradlew
```

Contributions are welocme ...
