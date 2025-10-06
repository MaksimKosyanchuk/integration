pipeline {
    agent any

    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello from Stage 1'
                sh 'date'
            }
        }
        stage('Stage 2') {
            steps {
                echo 'Hello from Stage 2'
                sh 'whoami'
            }
        }
    }
}
