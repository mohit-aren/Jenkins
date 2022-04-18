pipeline {
    agent { label 'main' }
    stages {
        stage('build') {
            steps {
		javac hello.java
                java hello
            }
        }
    }
}