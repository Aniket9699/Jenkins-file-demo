pipeline {
    agent any

    stages {
        stage('Stage 1 - Start') {
            steps {
                echo '🎬 Pipeline execution started!'
            }
        }

        stage('Stage 2 - Checkout Code') {
            steps {
                echo '📦 Simulating: Checking out code from Git...'
            }
        }

        stage('Stage 3 - Build') {
            steps {
                echo '🔧 Simulating: Building the application...'
            }
        }

        stage('Stage 4 - Test') {
            steps {
                echo '🧪 Simulating: Running unit tests...'
            }
        }

        stage('Stage 5 - Package') {
            steps {
                echo '📦 Simulating: Packaging the application...'
            }
        }

        stage('Stage 6 - Deploy') {
            steps {
                echo '🚀 Simulating: Deploying the application...'
            }
        }
    }

    post {
        success {
            echo '✅ The pipeline executed successfully!'
        }
        failure {
            echo '❌ The pipeline failed.'
        }
        always {
            echo '📋 Final cleanup or notification step (always runs).'
        }
    }
}
