pipeline{
  agent any
  stages{
    stage('build'){
      steps{
        nodejs('Node'){
          echo 'Building Application......'
          sh 'npm install'
        }
      }
    }
  } 
   
