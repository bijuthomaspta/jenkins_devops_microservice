pipeline {
  agent { docker { image 'maven:3.8.6-openjdk-18-slim' }}
  stages {
    stage ('build') {
      steps {
        sh 'mvn --version' 
        echo 'build'
      }
    }
  }
}       
