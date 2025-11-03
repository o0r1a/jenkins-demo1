pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Checking out code from GitHub...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running unit tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying to server (simulation)...'
            }
        }
    }
}
