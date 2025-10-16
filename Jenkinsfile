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
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
has context menu
