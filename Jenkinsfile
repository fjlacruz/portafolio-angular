pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. modificando'
            }
        }
        stage('Test') {
            steps {
                 bash 'npm run test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
