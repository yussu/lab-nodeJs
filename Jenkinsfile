pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the Node.js application...'
                sh 'npm install'
            }
        }

       stage('Test') 
            steps {
                echo 'Running tests...'
                sh 'npm test' // Replace 'npm test' with the actual command to run your tests (e.g., 'npm run test' or 'mocha')
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // You can add deployment steps here if needed.
            }
        }
    }
