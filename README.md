# Spring Boot Java Project for Maven

This repository contains a simple Java project utilizing Spring Boot and Maven. Follow the steps below to set up and test the project in your Linux environment.

## Prerequisites

Before starting, ensure you have Java and Maven installed:

1. **Install Java Development Kit (JDK)**:
   ```bash
   sudo apt-get update
   sudo apt-get install openjdk-17-jre -y

2. **Verify Java Installation**:
   ```bash
   java -version
3. **Install Maven**:
   ```bash
   sudo apt-get install maven -y
4. **Verify Maven Installation**:
   ```bash
   mvn -version

## Project Setup and Testing

5. **Clone the GitHub Repository**:
   ```bash
   git clone https://github.com/barlakshan/springboot-java-poject.git
   
6. **Navigate to Project Directory**:
   ```bash
   cd springboot-java-poject

7. **Navigate to Project Directory**:
   ```bash
   cd springboot-java-poject

## Configurations on Maven

8. **Validate: Checks and validates that the project setup is correct**:
   ```bash
   mvn validate

9. **Compile: Translates source code into executable code understood by computers.**:
   ```bash
   mvn compile

9. **Test: Run automated tests to verify functionality and catch errors.**:
   ```bash
   mvn test

9. **Package: Bundles compiled code and resources into distributable formats like JAR or WAR files.**:
   ```bash
   mvn package

9. **CInstall: Installs the packaged artifact into the local repository for use in other projects.**:
   ```bash
   mvn install

9. **Clean: Clean up an existing compiled files for refreshing.**:
   ```bash
   mvn clean   

## Configurations on Maven

## Deployment

**Finally, deploy our project and run the following code your artifact name "java -jar target/<artifact-name>"  and Access the Application at IP:8080**:
   ```bash
   java -jar target/springboot-java-web.jar
