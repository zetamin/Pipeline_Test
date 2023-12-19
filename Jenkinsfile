pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! Hello, World!'
        }

        failure {
            echo 'Pipeline failed!'
        }

        always {
            echo 'This will always run.'
        }
    }
}
