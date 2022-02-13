pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'mvn --version'
                sh 'java --version'
            }
        }
    }
}
