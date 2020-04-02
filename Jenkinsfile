pipeline {
    agent { docker { image 'jenkins//slave' } }
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}