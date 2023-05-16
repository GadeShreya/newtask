pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is build stage.'
            }
        }
        stage('Test') {
            steps {
                sh 'bash test.sh'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Successfully Deployed....'
            }
        }
    }
}
