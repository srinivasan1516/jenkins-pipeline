pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/srinivasan1516/jenkins-pipeline.git'
            }
        }

        stage('Build') {
            steps {
                sh 'bash build.sh'
            }
        }

        stage('Test') {
            steps {
                sh 'ls build'
            }
        }
    }
}

