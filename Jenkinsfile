pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/melathh/jenkins-test.git'
            }
        }
        stage('Build') {
            steps {
                sh 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                sh 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                sh 'Deploying...'
            }
        }
    }
}
has context menu
