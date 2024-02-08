pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Uno...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Uno...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
        stage('maven install') {
            steps {
                sh 'mvn clean install'
            }
       }
    }
}
