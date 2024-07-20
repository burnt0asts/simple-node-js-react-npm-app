pipeline {
    agent any
    tools {
        nodejs 'nodejs' // Make sure this matches the name you configured in Jenkins
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
