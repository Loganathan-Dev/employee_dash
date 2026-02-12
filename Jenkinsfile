pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'No build needed for static HTML/CSS project'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests configured'
            }
        }
    }
}
