pipeline {
    agent any
    stages {
        stage('Hello World') {
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
