pipeline {
    agent any 
    stages {
        stage('Stack') { 
            steps {
          sh "export AWS_DEFAULT_REGION=us-east-1"
          
sh "aws cloudformation  delete-stack --stack-name myteststack4"
          
          }
        }
       
        stage('validate') { 
            steps {
               sh "pwd"
            }
        }
    }
}
