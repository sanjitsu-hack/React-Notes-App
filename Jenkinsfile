pipeline {
    agent any

    stages {
        stage('init') {
            steps {
                bat 'npm install'
            }
        }
        stage('build') {
            steps {
                bat 'npm run build'
            }
        }
        stage('run') {
            steps {
                bat 'npm run dev'
            }
        }
    }
}
