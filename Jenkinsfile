pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                script {
                    // Checkout code from feature1 branch
                    checkout scm
                }
            }
        }
        
        stage('Compile and Run') {
            steps {
                script {
                    // Compile and run Sample.java
                    sh 'javac Sample.java'
                    sh 'java Sample'
                }
            }
        }
    }
}
