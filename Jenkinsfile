pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch:"main",url: 'https://github.com/Aniket-Naskulwar-2003/Jenkins.git', credentialsId: 'id'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage running...'
                sh 'echo Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing stage running...'
                sh 'echo Testing...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying app...'
                sh 'echo Deploy complete!'
            }
        }
    }
}
