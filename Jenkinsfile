pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                checkout scm


            }

        }

        stage('Build'){
            steps {
                sh 'echo "building application..."'
                sh 'cat app.txt'

            }
        }

    }

}
