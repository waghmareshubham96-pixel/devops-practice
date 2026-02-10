pipeline {
    agent any

    stages {
        stage('Command Failure') {
            steps {
                sh 'exit 0'
                echo 'You will not see this'
            }
        }
    }
}
