pipeline {
    agent any

    stages {
        stage('Exit 0 Test') {
            steps {
                sh 'echo "Running command"'
                sh 'exit 1'
                echo 'Stage completed'
            }
        }
    }
}
