pipeline{
    agent any
    environment{
        ENV_URL = "pipeline.google.com"               // pipeline variable or global variable
    }
    stages{
        stage("Stage One"){
            steps{
                
                echo "This is stage one"
                echo "Name of the url is ${ENV_URL}"
            
            }
        }

        stage("Stage Two"){
             environment{
        ENV_URL = "stage.google.com"               // stage variable 
       }
            steps{
                echo "This is stage Two"
                 echo "Name of the url is ${ENV_URL}"
            }
        }

         stage("Stage Three"){
            steps{
                echo "This is stage Three"
                echo "Name of the url is ${ENV_URL}"
            }
        }
    }
}