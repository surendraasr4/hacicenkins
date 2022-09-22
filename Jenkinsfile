pipeline {
  environment {
    imagename = "surendradockerhubreg/hashedin"
    registryCredential = 'docker'
    dockerImage = ''
  }
  agent any
  stages {
    stage('Cloning Git') {
      steps {
 //       git([url: 'https://github.com/surendraasr4/hacicenkins.git', branch: 'master', credentialsId: 'docker'])
 	checkout scm

      }
    }
    stage('Building image') {
      steps{
     
      sh "echo AWSKEY && sleep 10"


          }
      }
   
    
    
  }
}
