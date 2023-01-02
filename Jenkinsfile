pipeline {
  agent any
  environment {
    dockerHome = tool 'my_docker'
    mavenHome = tool 'my_maven'
    PATH = "$dockerHome/bin:$mavenHome/bin:$PATH"
  }
  stages {
    stage ('build') {
      steps {
        sh 'mvn --version'
        sh 'docker version'
        echo "build"
        echo "path= $path"
        echo "Build_numbe= $env.BUILD_NUMBER"
        echo "build_id= $env.BUILD_ID"
        echo "job_name= $env.JOB_NAME"
        echo "Build_tag= $env.BUILD_TAG"
      }
    }
  }
}       
