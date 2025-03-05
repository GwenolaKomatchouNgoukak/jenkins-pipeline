pipeline {
    agent any

    stages {
        stage('CodeScan'){
            steps {
                sh 'trivy --version'
            }
        }
        stage('dockerImageBuild'){
            steps {
                sh 'docker -v'
            }
        }
        stage('push image'){
            steps{
                sh 'docker ps'
            }
        }
    }
}