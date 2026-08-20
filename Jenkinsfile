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
        stage('Test3') {
            steps {
                echo 'Running tests3...'
            }
        }
        stage('Test1') {
            steps {
                echo 'Running tests1...'
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
