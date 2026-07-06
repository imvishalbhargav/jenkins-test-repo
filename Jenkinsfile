pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checkout ho raha hai...'
            }
        }
        stage('Build') {
            steps {
                echo 'Build step chal raha hai...'
                sh 'ls -la'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing ho rahi hai...'
                sh 'echo "Sab sahi chal raha hai!"'
            }
        }
    }
}
