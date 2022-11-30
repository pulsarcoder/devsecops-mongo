pipeline {
    agent any

    stages {
        stage('Chekout') {
            steps {
                git url: 'https://github.com/pulsarcoder/devsecops-mongo.git', branch: 'main'
                echo 'Checkout Completed'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
