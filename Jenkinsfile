pipeline {
    agent any
    environment {
    }
    stages {
        stage('clean') {
            steps {
                echo 'clean'
            }
        }
        stage('Build') {
            steps {
                dir('home'){
                    echo 'build'
                }
            }
        }
    }
}