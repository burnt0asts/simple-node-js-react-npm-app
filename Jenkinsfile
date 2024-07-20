pipeline {
    agent any
    tools {
        nodejs 'NodeJS 22.4.0' // Use the exact name of the Node.js installation
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }

	stage('Test') { 
            steps {
                sh './jenkins/scripts/test.sh' 
            }
        }

    }

}
