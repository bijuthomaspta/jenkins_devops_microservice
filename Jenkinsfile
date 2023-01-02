pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo "build"
//         echo "path= $path"
        echo "Build_numbe= $env.BUILD_NUMBER"
        echo "build_id= $env.BUILD_ID"
        echo "job_name= $env.JOB_NAME"
        echo "Build_tag= $env.BUILD_TAG"
      }
    }
  }
}       
