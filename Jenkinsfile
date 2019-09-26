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
        stage('Package') {
            steps {
                echo 'packaging tarball'
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
