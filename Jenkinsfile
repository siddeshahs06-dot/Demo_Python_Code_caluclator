pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                sh 'python3 --version'
            }
        }

        stage('hello') {
            steps {
                sh 'python3 hello.py'
            }
        }

    }
}
