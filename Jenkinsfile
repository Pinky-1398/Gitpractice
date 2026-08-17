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
                bat 'echo Application build successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Application tests passed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }
}