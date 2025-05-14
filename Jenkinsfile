pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    docker.build('python-jenkins-demo')
                }
            }
        }

        stage('Run Tests') {
            steps {
                echo 'Running tests (placeholder)...'
                // You can add test commands here later.
            }
        }
    }
}

