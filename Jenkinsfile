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
                bat '"C:\Users\geeta\AppData\Local\Programs\Python\Python310\python.exe" app.py'
            }    
        }
    }
}
