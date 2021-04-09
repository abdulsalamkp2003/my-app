pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "docker build -t test:latest ."
            }
        }
    }
}
