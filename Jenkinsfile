pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/chetnaranglani/Project-1.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project...'
            }
        }

    }
}
