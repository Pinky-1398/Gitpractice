pipeline {
    agent any

    environment {
        DEMO_SECRET = credentials('demo-secret')
    }

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }

        stage('Credentials Test') {
            steps {
                echo 'Credential is available to the pipeline'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}