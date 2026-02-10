pipeline {
    agent any

    stages {
        stage('Exit 0 Test') {
            steps {
                sh 'echo "Running command"'
                sh 'exit 0'
                echo 'Stage completed'
            }
        }
    }
}
