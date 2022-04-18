// Example of Jenkins pipeline script

pipeline {
  agent any
  stages {
    stage("Build") {
       steps {
          // Just print a Hello, Pipeline to the console
          echo "Hello, Pipeline!"
          // Compile a Java file. This requires JDKconfiguration from Jenkins
          javac ./HelloWorld.java

          java HelloWorld

       }
   }
   // And next stages if you want to define further...
 } // End of stages
} // End of pipeline