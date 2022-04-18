// Example of Jenkins pipeline script

pipeline {
  agent any
  stages {
    stage("Build") {
       steps {
          // Just print a Hello, Pipeline to the console
          echo "Hello, Pipeline!"
          // Compile a Java file. This requires JDKconfiguration from Jenkins
          javac HelloWorld.java
          // Execute the compiled Java binary called HelloWorld. This requires JDK configuration from Jenkins
          java HelloWorld
          // List the files in current directory path by executing a default shell command
          sh "ls -ltr"
       }
   }
   // And next stages if you want to define further...
 } // End of stages
} // End of pipeline