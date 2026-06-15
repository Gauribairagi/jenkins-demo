pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }
stage('Check Python') {
    steps {
        bat 'where python'
        bat 'python --version'
    }
}
        stage('Run Python Script') {
            steps {
                bat 'python hello.py'
            }
        }
    }
}