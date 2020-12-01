## seisAnt
### build.xml (xml)
# Project element
### All build files require the project element and at least one target element.
### Project element has three attributes: name, default : this attribute specifies which target should be considered as the default, basedir : the base directory or the root folder. 
# Target element
### Ant target is a sequence of tasks to be executed to perform a part (or whole) of the build process. 
### Ant targets are defined by the user
# Common Targets
###  Clean:  An Ant target for cleaning up the build output directory
### Compile: for compiling the Java source code in the project
### Jar: for creating a JAR file from the compiled classes
### Test: for running all unit tests for the Java code
### Javadoc: for creating JavaDoc comments for the code.
# Run a ant file
### Create a folder with build.xml file with the content listed below
### navigate to the folder were the build.xml file 
### And run ant from the terminal
command: ant Target name
  
