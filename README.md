
# maven-project

This repository contains a Maven project. The project was initialized using the maven-archetype-quickstart archetype and includes a basic directory structure for a Java application. I've built the project using Maven, resulting in the generation of the artifact.



## getting started
First create an ec2 instance of ubuntu type in AWS and connect to that instance.

Now execute the below commands one by one.
1. sudo apt-get update -y. 
This command updates the package lists for repositories configured in APT (Advanced Package Tool) on a Linux system, ensuring that the system has the latest information about available packages. The -y flag automatically confirms any prompts during the update process, allowing for unattended updates.


2. sudo apt install openjdk-11-jre -y.  
This command installs the OpenJDK 11 Java Runtime Environment (JRE) on a Linux system. This is required for running Java applications, including Maven, which relies on Java for its execution environment. The JRE provides the necessary runtime environment for Java-based programs to execute without the need for development tools.
You can check java version using "java --version"

3. sudo apt-get install maven -y. 
This command installs Apache Maven build automation tool.
You can check maven version using "mvn --version"


## to build artifact
Now clone this repo using "git clone <repo URL>" command.
Then cd into project's main directory. Then
Execute the below commands:  
1. mvn validate: 
This checks whether the project is correct and all necessary information is available, without executing the build process. It verifies the project's structure, dependencies, and configurations.

2. mvn compile: 
 Compiles the source code of the project.

3. mvn test:  
Runs the tests for the project.

4. mvn package:
Packages the compiled code into a distributable format, such as a JAR, WAR, or EAR file.  
Now you can cd to your target folder (which is in the project's main folder) to see the artifact.




