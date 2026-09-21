pipeline {
    agent any

    stages {

        stage('Clone GitHub Repository') {
            steps {
                git 'https://github.com/Vrushk13/Microservices-app.git'
            }
        }

        stage('Check Files') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
