pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building...."
                sh "cmake ."
            }
        }
        stage('Test') {
            steps {
                echo "Running ...."
                sh "make hello"
            }
            
        }
    }
}