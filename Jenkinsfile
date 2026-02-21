pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/chetnaranglani/Project-1.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'mvn test'
            }
        }

    }
}
