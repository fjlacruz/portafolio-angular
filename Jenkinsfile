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
                 sh 'npm run test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
