pipeline {
    agent { dockerfile true }
    stages {
        stage('Build Image') {
            steps {
                sh 'mvn --version'
                sh 'java --version'
            }
        }
        stage('Compile') {
            steps {
                sh 'mvn clean compile'
               
            }
        }    
        
         stage('Test Compile') {
            steps {
                sh 'mvn clean test-compile'
               
            }
             
         }
         stage('Test') {
            steps {
                sh 'mvn clean test'
               
            }    
        }
    }   
 }
