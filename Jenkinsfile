pipeline {
    agent {
        docker { image 'node:21-alpine'}
    }

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('test') {
            steps {
                sh 'node --version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }

    }
}

