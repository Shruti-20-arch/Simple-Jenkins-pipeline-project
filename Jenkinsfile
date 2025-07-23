pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'javac Welcome.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Welcome'
            }
        }
    }
}
