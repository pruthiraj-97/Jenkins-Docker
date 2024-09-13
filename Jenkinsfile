pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "Build"
            }
        }stage("Test"){
            steps{
                echo "Test"
            }
        }stage("Deploy"){
            steps{
                echo "Deploy"
            }
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}