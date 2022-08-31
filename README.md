# NRODCamelTesting
Code for debugging NROD propertyNames issue

Camel/  is a directory containig the slightly modified Camel 3.18.1 source files needed to recreate JAR

CamelRouter/  is the source to reate a Camel-only executable JAR that listens to the NROD feeds

CamelRouter.jar  is the executable JAR built on Ubuntu 20.04 with Java 11.0.16

logs/ is a directory of examples of the EOFException and the JMS messages that caused it

