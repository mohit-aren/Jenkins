// Example of Jenkins pipeline script

pipeline {
  agent any
  stages {
    stage("Build") {
       steps {
          // Just print a Hello, Pipeline to the console
          echo "Hello, Pipeline!"
          // Compile a Java file. This requires JDKconfiguration from Jenkins
          bat "javac HelloWorld.java"
       }
    }
    stage("Execute") {
       steps {
          // Just print a Hello, Pipeline to the console
          echo "Hello, Pipeline!"
          // Compile a Java file. This requires JDKconfiguration from Jenkins
          bat "java HelloWorld"
       }
   }
 } // End of stages
} // End of pipeline
