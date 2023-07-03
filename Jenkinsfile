pipeline{
    agent any
    environment{
        ENV_URL = "pipeline.google.com"
    }
    stages{
        stage("Stage One"){
            steps{
                sh ...
                echo "This is stage one"
                echo Name of the url is ${ENV_URL}
                ...
            }
        }

        stage("Stage Two"){
            steps{
                echo "This is stage Two"
            }
        }

         stage("Stage Three"){
            steps{
                echo "This is stage Three"
            }
        }
    }
}