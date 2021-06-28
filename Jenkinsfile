Pipleline {
    agent any
    stages {
        stage('Build') {
            step {
                sh 'echo "Building...."'
                sh 'cmake .'
            }
        }
        stage('Test') {
            sh 'echo "Running ...."'
            sh 'make hello'
        }
    }
}