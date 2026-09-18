#Demo Java DevOps Project:

This is a Java Maven application created for learning DevOps and CI/CD.


## Technologies:

- Java 21
- Maven
- Git
- GitHub
- Jenkins
- Ansible
- AWS


## Project Goal:

The goal of this project is to create an automated CI/CD pipeline:

GitHub → Jenkins → Maven → Ansible → AWS EC2

                 DEVELOPER
                     |
                     | git push
                     ↓
                  GITHUB
                     |
                     | Pull source code
                     ↓
                 JENKINS
                     |
                     | Maven Build
                     ↓
              Java Application
                   Build
                     |
                     | .jar file
                     ↓
                 ANSIBLE
                     |
                     | SSH
                     ↓
              AWS EC2 SERVER
                     |
                     | Run Java Application
                     ↓
                APPLICATION

                
## Project Structure:

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

## Maven Commands:

### Compile the project

```bash
mvn compile

## Running the Application

First package the application:

```bash
mvn package


## Testing:

Unit tests are located in:

```text
src/test/java/com/example/AppTest.java


## CI/CD Plan:

This project will be extended with an automated CI/CD pipeline.

The planned deployment flow is:

```text
Developer
    ↓
VS Code
    ↓
Git
    ↓
GitHub
    ↓
Jenkins
    ↓
Maven Build
    ↓
Unit Tests
    ↓
Ansible
    ↓
AWS EC2
    ↓
Java Application.
