pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                sh 'echo "Hello World"'  // Test webhook
                sh 'date'
            }
        }
        stage('Test Webhook') {
            steps {
                sh 'echo "Webhook is working!"'
            }
        }
    }
}