pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout successful'
            }
        }

        stage('Build') {
            steps {
                bat 'docker --version'
                bat 'docker build -t studentapp .'
            }
        }
    }
}
