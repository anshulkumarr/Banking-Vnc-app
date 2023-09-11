Account-Service Backend
--
A Spring boot microservice project which takes the account details and save in mysql database.

Prerequisites
--
## Install Java on Ubuntu 22.04
### Update & Upgrade pkgs
``` sudo apt update && apt upgrade ```
### Install java
``` sudo apt install openjdk-17-jdk ```
### Check java version 
``` java --version ```

## Install Maven
### Download maven 
``` wget https://dlcdn.apache.org/maven/maven-3/3.8.5/binaries/apache-maven-3.8.5-bin.tar.gz ```
### Exract the file 
``` tar -xvf apache-maven-*-bin.tar.gz ```
### Move it to /usr/share/
``` sudo mv apache-maven-3.8.5 /usr/share/maven ```
###  Add the Maven folder to the System path
``` echo 'export PATH="$PATH:/usr/share/maven"' >> ~/.bashrc
    echo 'export PATH="$PATH:/usr/share/maven/bin"' >> ~/.bashrc
```
### Reload Bash profile
``` source ~/.bashrc ``` 

### Check the MVN version
``` mvn -v ```

How to Download and use the application
--
### Git clone the project using 
``` https://github.com/pavankumar0077/Client-Server-Vnc-Project.git ```
### Use any IDE like STS or Eclipse download link is here
``` https://download.springsource.com/release/STS4/4.19.1.RELEASE/dist/e4.28/spring-tool-suite-4-4.19.1.RELEASE-e4.28.0-linux.gtk.x86_64.tar.gz ```
### Import and Run the application (GUI)
1) Select File (Top-left corner) --> Select Open Projects from file system --> Select file path using Directory option --> and Click on Finish
2) Right click on the project --> Run as -->  Spring boot application

### Run the application using CLI
```
1) Go the path where application is clone and cd to Account-Service
2) 