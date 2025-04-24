pipeline {
    agent any  // Run on any available agent

    stages {
        stage('Checkout') {
            steps {
                // Clone the source code from Git
                git 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                // Example build command
                sh 'echo Build successful!'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example test command
                sh 'echo All tests passed!'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying ${APP_NAME}..."
                // Example deploy command
                sh 'echo Deployment complete!'
            }
        }
    }
