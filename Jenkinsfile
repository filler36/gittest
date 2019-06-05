pipeline {
    agent { label 'vm2' }
    stages {
        stage('Greetings222') {
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
