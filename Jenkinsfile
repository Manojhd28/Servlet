pipeline {
    agent any

    tools {
        maven 'maven' 
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
