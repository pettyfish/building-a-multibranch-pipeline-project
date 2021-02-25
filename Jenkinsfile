
pipeline {
    agent any

    stages {
        stage('Prepare') {
            steps {
                sh 'echo $PATH && node -v && npm -v'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}