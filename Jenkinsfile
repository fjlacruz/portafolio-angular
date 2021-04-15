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
                 sh 'ng test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
