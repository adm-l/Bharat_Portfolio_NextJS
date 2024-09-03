pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from GitHub
                git branch: 'main', url: 'https://github.com/adm-l/Bharat_Portfolio_NextJS.git'
            }
        }
        
        stage('Install Dependencies') {
            steps {
                // Install the necessary dependencies for the Next.js project
                sh 'npm install'
            }
        }
        
        stage('Build') {
            steps {
                // Example build step (replace with your actual build command)
                 sh 'npm run build'
            }
        }

        stage('Test') {
            steps {
                // Example test step (replace with your actual test command)
                 sh 'npm run test'
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
