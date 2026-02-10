pipeline {
    agent any

    stages {
        stage('Command Failure') {
            steps {
                sh 'exit 1'
                echo 'You will not see this'
            }
        }
    }
}
