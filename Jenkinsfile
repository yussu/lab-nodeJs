pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the Node.js application...'
                sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // You can add deployment steps here if needed.
            }
        }
    }
}
