pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building...."
                sh "cmake ."
                sh "make hello"
            }
        }
        stage('Test') {
            steps {
                echo "Running ...."
                echo "./hello"
            }
            
        }
    }
}