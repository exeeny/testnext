pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Install') {
            steps {
                echo 'Installing dependencies...'
            }
        }

        stage('Lint') {
            steps {
                echo 'Running lint...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
    }
}
