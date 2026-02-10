pipeline {
    agent any

    stages {
        stage('Command Failure') {
            steps {
                sh 'somewrongcommand'
                echo 'You will not see this'
            }
        }
    }
}
