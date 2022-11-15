pipeline {
    agent {
        docker {
            image 'node:lts-bullseye-slim' 
            args '-p 2376:2376' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}