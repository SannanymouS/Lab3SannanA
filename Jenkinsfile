pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/991344581/Lab3SannanA.git'
            }
        }

        stage('Task 1 - Print Working Directory') {
            steps {
                sh 'pwd'
            }
        }

        stage('Task 2 - List Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
