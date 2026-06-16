pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/tuhainkaun/jenkins-practical.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build step running"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy step running"
            }
        }
    }
}
