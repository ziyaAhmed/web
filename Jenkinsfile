pipeline {
    agent any

    stages {
        stage('Checkout HTML') {
            steps {
                checkout scm
            }
        }

        stage('Copy to Web Server') {
            steps {
                script {
                    // Replace 'index.html' with your HTML file's name
                    sh 'cp index.html /var/www/html/'
                }
            }
        }
    }
}

