* Build under linux
TOMCAT_HOME=/some/path/tomcat ./build

* Configure in Tomcat
Add following entry to conf/server.xml:

<Listener className="Log4JInitializer" propertiesFile="${catalina.base}/log4j.properties"/>

Put log4j-initializer.jar to server/lib directory.

* Notes
Build instructions are for Apache Tomcat 5.5

