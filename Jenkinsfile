pipeline {
    agent any

    tools {
        maven 'Maven_3.9.6' // Must match the name in Jenkins config
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Manojhd28/Servlet.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
