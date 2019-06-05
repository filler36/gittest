pipeline {
    agent any
    stages {
        stage('Hello stage') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('OS release') {
            steps {
                sh 'cat /etc/os-release'
            }
        }
    }
}
