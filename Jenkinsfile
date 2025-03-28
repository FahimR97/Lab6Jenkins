pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                sh 'echo "Hello World"'
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