pipeline {
    agent any
    stages {
        stage('Check Docker Installation') {
            steps {
                script {
                    try {
                        sh 'docker --version'
                    } catch (Exception e) {
                        echo 'Docker is not installed or not accessible.'
                    }
                }
            }
        }
    }
}

