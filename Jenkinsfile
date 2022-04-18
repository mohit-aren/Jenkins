pipeline {
    agent { label 'main' }
    stages {
        stage('build') {
            steps {
                java hello.java
            }
        }
    }
}