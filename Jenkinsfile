pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from GitHub
                git branch: 'main', url: 'https://github.com/adm-l/Bharat_Portfolio_NextJS.git'
            }
        }

        stage('Build') {
            steps {
                // Example build step (replace with your actual build command)
                sh 'echo "Building the project..."'
            }
        }

        stage('Test') {
            steps {
                // Example test step (replace with your actual test command)
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                // Example deploy step (replace with your actual deploy command)
                sh 'echo "Deploying the application..."'
            }
        }
    }

    post {
        always {
            // Cleanup, notifications, etc.
            echo 'Pipeline completed.'
        }
    }
}
