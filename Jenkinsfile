Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any

    stages {
		stage('Checkout') {
			steps {
				echo 'Checkout Source..'
				checkout scm
			}
		}
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}