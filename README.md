#Louis Maven Archetype

---
###Description:
This is a Maven archetype that contains files and configurations that I would otherwise have to create by hand.

####Things it does:
* Tells Maven that this project uses Java 6
* Tells Maven to include all libraries in the JAR excluding test libraries (ie JUnit)
* Gets Maven to compile the JAR as executable with the value inputted for mainClass as the main class
* Creates a main class and a corresponding test class named using mainClass variable in specified package
* Fills in artifactId, name, description fields in pom.xml with the values of those variables
* Specifies that the default goal should be package
* Sets groupId to net.clonecomputers.lab and version to 0.0.1-SNAPSHOT

####Required Variables:
* artifactId
* name
* description
* package
* mainClass

---
###Goals:
####Completed:
* Almost everything
* Add main and test class with filtered names
