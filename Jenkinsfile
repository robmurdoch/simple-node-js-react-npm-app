pipeline {
    agent { docker { image 'codecrunchers/jenkins-node-slave' } }
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}