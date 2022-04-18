pipeline {
    agent { label 'main' }
    stages {
        stage('build') {
            steps {
                sh 'java hello.java'
            }
        }
    }
}