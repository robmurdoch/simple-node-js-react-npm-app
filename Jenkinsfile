pipeline {
    agent { 
        label 'node' 
    }
    environment {
        CI = 'true' 
    }
    stages {
        stage('build') {
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