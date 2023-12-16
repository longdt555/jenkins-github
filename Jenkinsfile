pipeline {
    agent any
    stages {
	stage('Clone') {
            steps {
				git 'https://github.com/longdt555/jenkins-github.git'
                echo 'Cloning..'
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
