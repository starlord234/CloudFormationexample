pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name CloudFormationexample --template-body file://SecondBucket.yaml --region 'us-west-2'"
              }
             }
            }
            }
