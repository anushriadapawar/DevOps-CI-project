pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/anushriadapawar/DevOps-CI-project.git'
            }
        }

        stage('Install dependencies') {
            steps {
                bat 'pip install -r requirements.txt'
            }
        }

        stage('Run Tests') {
            steps {
                bat 'pytest'
            }
        }

    }
}