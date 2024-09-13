pipeline {
    agent any
    stages {
        stage("Check Docker") {
            steps {
                sh 'docker --version'
            }
        }
        stage("Build") {
            steps {
                echo "Build"
            }
        }
        stage("Test") {
            steps {
                echo "Test"
            }
        }
        stage("Deploy") {
            steps {
                echo "Deploy"
            }
        }
    }
    post {
        always {
            echo "======== always ========"
        }
        success {
            echo "======== pipeline executed successfully ========"
        }
        failure {
            echo "======== pipeline execution failed ========"
        }
    }
}
