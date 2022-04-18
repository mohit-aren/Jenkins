pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                java hello.java
            }
        }
    }
}