pipeline {
    agent any

    stages {
      
        stage('Build the application') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test the application') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy the application') {
            steps {
                echo 'Deploying application...'
            }
        }
    }

    post {
        always {
            echo 'Pipeline execution completed.'
        }

        success {
            echo 'Build Successful!'
        }

        failure {
            echo 'Build Failed!'
        }
    }
}
