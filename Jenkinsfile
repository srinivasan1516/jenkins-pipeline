pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/srinivasan1516/jenkins-pipeline.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build stage executed successfully"
                sh 'ls -la'
            }
        }
    }
}
