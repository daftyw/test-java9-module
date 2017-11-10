## Java 9 Modules

Java 9 Module with Maven support test artifact

### Project Requirement
* Need sub-project (module)
* Toolchain for Java 9 compiler location, need ~/.m2/toolchains.xml
* each of them need to be identified in <modules> for parent project and <dependencies> on each other pom.xml
* source and target can be 9 or 1.9
### Module Info Requirement
* Need _exports_ to tell which module can be used by other modules
* Need _requires_ to tell which module the module want to use

   
