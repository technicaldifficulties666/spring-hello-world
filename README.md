# spring-hello-world README
## Overview
This is a Spring Boot web project that demonstrates how to build a simple web application using Spring. The app is a classic “Hello World!” endpoint which any browser can connect to. You can even tell it your name, and it will respond in a more friendly way.


## Getting Started

NOTE: This guide assumes windows installation

To get started, you'll need to have  Java JDK version 17 and Gradle 8.6 installed on your machine 

Follow this guide to install and switch between multiple JDKs in windows: https://www.happycoders.eu/java/how-to-switch-multiple-java-versions-windows/ 
Follow guide on https://spring.io/quickstart for starting a new Spring Boot project

Change the build.gradle file as done here

add gradle.properties file in the project directory and add the line:
```bash
org.gradle.java.home =  C:/Program Files/Java/jdk-17 ##<Path to the JDK you want to use for your project (JDK 17)>
```

Optional: set distributionUrl is set to https\://services.gradle.org/distributions/gradle-8.6-bin.zip in gradle-wrapper.properties
```bash
distributionUrl=https\://services.gradle.org/distributions/gradle-8.6-bin.zip
```

For running app: In the terminal, go to project directory and run commands
```bash 
./gradlew build
gradle run 
```
Run app on http://localhost:8080/hello

