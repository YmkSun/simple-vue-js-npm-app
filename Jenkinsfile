pipeline {
    agent any
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                bat 'npm install'
            }
        }
        stage('Deliver') {
            steps {
				bat'npm run build'
            }
        }
    }
}
