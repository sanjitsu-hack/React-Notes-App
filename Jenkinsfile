pipeline {
    agent any

    stages {
        stage('init') {
            steps {
                sh 'npm install'
            }
        }
        stage('build') {
            steps {
                sh 'npm run build'
            }
        }
        stage('run') {
            steps {
                sh 'npm run dev'
            }
        }
    }
}
