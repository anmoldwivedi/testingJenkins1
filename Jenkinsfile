pipeline {
    agent any
    stages {
        stage('Build') {
            step {
                echo "Building...."
                sh "cmake ."
            }
        }
        stage('Test') {
            step {
                echo "Running ...."
                sh "make hello"
            }
            
        }
    }
}