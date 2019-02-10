# demo-jpacktool-update4j

Sample Maven Project to use [jpacktool-maven-plugin](https://github.com/agilhard-oss/jpacktool/tree/master/jpacktool-maven-plugin)
and [update4j](https://github.com/update4j/update4j) together in a project.

## Parent Module

This is the Git and Maven Parent-Module of jpackager-update4j-maven example.


To get the full source code including the submodules execute:

git clone --recursive https://github.com/bei/demo-jpacktool-update4j.git

After running ...

mvn -Pprepare clean install

... and ..

mvn clean install


The ZIP file for the Java Runtime includinge the Demo Bootstrap Application 
can be found at ...

demo-pack/target/maven-jpacktool/build/demo-business-jpacktool/demo-business-jpacktool-jlink/target/demo-business-jpacktool-jlink-1.0.0-SNAPSHOT.zip 

and the ZIP file for the Demo Business Application to put onto the localhost
Webserver running on port 8080 can be found at ...

demo-pack/target/demo-business-jpacktool-jlink-1.0.0-SNAPSHOT.zip 



