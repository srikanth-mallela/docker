pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/your-user/your-repo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo Building...'
            }
        }
        stage('Test') {
            steps {
                sh 'echo Testing...'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploying...'
            }
        }
    }
}
