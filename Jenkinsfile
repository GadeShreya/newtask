pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is build stage.'
            }
        }
        stage('test') {
            steps {
                sh 'bash test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Successfully Deployed....'
            }
        }
    }
}
