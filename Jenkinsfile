pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking out Brew Haven project from GitHub'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Brew Haven Docker image build stage'
            }
        }

        stage('Kubernetes Deploy') {
            steps {
                echo 'Brew Haven Kubernetes deployment stage'
            }
        }

    }

    post {
        success {
            echo 'Brew Haven CI/CD Pipeline completed successfully!'
        }

        failure {
            echo 'Brew Haven CI/CD Pipeline failed.'
        }
    }
}