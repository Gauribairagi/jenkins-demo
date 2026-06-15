pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Compile Java') {
            steps {
                bat 'javac hello.java'
            }
        }

        stage('Run Java Program') {
            steps {
                bat 'java hello'
            }
        }
    }
}