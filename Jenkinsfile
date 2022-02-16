pipeline {
    agent {
        docker { image 'ros:foxy' }
    }
    stages {
        stage('Build') {
            steps {
                sh 'git --version'
            }
        }
    }
}