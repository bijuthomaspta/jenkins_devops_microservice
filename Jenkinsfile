pipeline {
  agent {docker { image 'maven:3.63'}}
  stages {
    stage ('build') {
      steps {
        sh ' mvn --version' 
        echo 'build'
      }
    }
  }
        
