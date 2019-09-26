pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source' 
            }
        }
        stage('Build') {
            steps {
                echo 'Building binaries' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to SIT' 
            }
        }
        stage('Test') {
            steps {
                echo 'Run integration tests' 
            }
        }
    }
}
