# A Simple JMeter Load Testing on Openshift

This project consist of JMeter maven plugin, the purpose is to do a load testing in Openshift environment based on a parameterized configuration and a specific jmx file.  

## Run the project using Maven
```
mvn clean verify -Dthreads=5 -Drampup=5 -Dloops=5 -Durl=localhost -Dport=8080 -Dtestfile=test01.jmx
```