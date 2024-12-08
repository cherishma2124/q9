pipeline {
    agent any
    stages {
        stage('Declarative: Checkout SCM') {
            steps {
                git branch: 'main', url: 'https://github.com/cherishma2124/q9.git'
            }
        }
        stage('Build') {
            steps {
                bat 'echo Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'echo Testing the application...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                bat 'echo Deployment complete!'
            }
        }
    }
}
