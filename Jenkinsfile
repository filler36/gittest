pipeline {
    agent any
    stages {
        stage('Greetings') {
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
