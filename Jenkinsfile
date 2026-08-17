pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code checked out from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
                bat 'python app/app.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'python app/app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }
}