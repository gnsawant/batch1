pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/gnsawant/batch1.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'python --version'
            }
        }
    }
}
