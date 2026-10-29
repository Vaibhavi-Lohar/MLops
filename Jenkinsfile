pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps { checkout scm }
        }
        stage('Run App') {
            steps { bat '"C:\\Users\\Shreya\\AppData\\Local\\Programs\\Python\\Python310\\python.exe" hello.py' }
        }
    }
}
