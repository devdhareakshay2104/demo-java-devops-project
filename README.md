# Java DevOps Project

This is a Java Maven application created for learning DevOps and CI/CD.

## Technologies

- Java 21
- Maven
- Git
- GitHub
- Jenkins
- Ansible
- AWS

## Project Goal

The goal of this project is to create an automated CI/CD pipeline:

GitHub → Jenkins → Maven → Ansible → AWS EC2

## Project Structure

```text
java-devops-project
├── .gitignore
├── pom.xml
├── README.md
└── src
    └── main
        └── java
            └── com
                └── example
                    └── App.java

## Maven Commands

### Compile the project

```bash
mvn compile

## Running the Application

First package the application:

```bash
mvn package