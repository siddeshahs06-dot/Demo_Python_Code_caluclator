pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code...'
            }
        }

        stage('Run Python') {
            steps {
                bat 'python --version'
                bat 'pip --version'
            }
        }

        stage('Run Script') {
            steps {
                bat 'hello.py'
            }
        }
    }
}
