pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps { checkout scm }
        }
        stage('Run App') {
            steps { sh 'python3 hello.py' }
        }
    }
}