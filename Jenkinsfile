pipeline {
    agent any

    stages {

        stage('Install dependencies') {
            steps {
                bat '"C:\Users\ANUSHRI\AppData\Local\Programs\Python\Python314\Scripts\pip.exe" install -r requirements.txt'
            }
        }

        stage('Run Tests') {
            steps {
                bat '"C:\Users\ANUSHRI\AppData\Local\Programs\Python\Python314\python.exe" -m pytest'
            }
        }

    }
}