pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/riti-1904/Jenkins-DT3.git'
            }
        }
        stage('Build') {
            steps {
                sh 'g++ -o program main.cpp'
            }
        }
        stage('Run') {
            steps {
                sh './program'
            }
        }
    }
}
