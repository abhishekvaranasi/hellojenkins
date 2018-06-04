pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'python hello_jenkins.py'
            }
        }
        stage('Test') {
            steps {
                echo 'This is testing stage'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment stage completed!'
            }        
        }
    }
}
