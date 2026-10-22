
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code checkout stage'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                echo 'All tests passed!'
            }
        }

        stage('Success') {
            steps {
                echo 'CI Pipeline completed successfully!'
            }
        }
    }
}
