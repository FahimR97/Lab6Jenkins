pipeline {
    agent { label 'any' }    // or just use: agent any
    
    stages {
        stage('Hello') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('Test Webhook') {
            steps {
                sh 'echo "Webhook test"'
            }
        }
    }
}