pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'docker build -t devops-demo .'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running tests...'
            }
        }

        stage('Push') {
            steps {
                sh 'echo Push to registry'
            }
        }
    }
}
