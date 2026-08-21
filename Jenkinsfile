pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Run Application') {
            steps {
                echo 'run application'
                bat 'python app.py'
            }    
        }
    }
}
