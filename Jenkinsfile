pipeline {
    agent any  // Runs on any available Jenkins agent

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/user/repository.git'  // Clone repository
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building application...'  // Simulating a build step
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running tests...'  // Simulating tests
            }
        }
    }
}
