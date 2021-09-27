* install maven in your PC
* generate simple maven project using below command in your project directory.

mvn archetype:generate -DgroupId=com.ace.bank -DartifactId=bank-test -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false

* we can also generate webapp using archetype maven-archetype-webapp
mvn archetype:generate -DgroupId=com.ace.group -DartifactId=login -DarchetypeVersion=1.2.0-SNAPSHOT  -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false

* we can also generate j2ee application maven-archetype-j2ee-simple

mvn archetype:generate -DgroupId=com.ace.group -DartifactId=login -DarchetypeVersion=1.2.0-SNAPSHOT  -DarchetypeArtifactId=maven-archetype-j2ee-simple -DinteractiveMode=false
