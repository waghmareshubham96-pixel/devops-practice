pipeline {
    agent any

    tools {
        git 'Default'
    }

    stages {

        stage('Checkout Code') {
            steps {
                echo 'Pulling code from GitHub...'
                checkout scm
            }
        }

        stage('Build Step') {
            steps {
                echo 'Simulating build process...'
                sh 'echo "Build successful!"'
            }
        }

        stage('Test Step') {
            steps {
                echo 'Running test simulation...'
                sh 'echo "All tests passed!"'
            }
        }

        stage('Deploy Step') {
            steps {
                echo 'Simulating deployment...'
                sh 'echo "Deployment completed!"'
            }
        }
    }
}
