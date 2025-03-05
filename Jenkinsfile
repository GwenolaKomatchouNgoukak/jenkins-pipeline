pipeline {
    agent any

    stages {
        stage('clone'){
            steps {
                sh 'echo "clone"'
            }
        }
        stage('test'){
            steps {
                sh 'echo "Test"'
            }
        }
        stage('create file'){
            steps{
                sh 'touch test-$BUILD_ID'
            }
        }
    }
}