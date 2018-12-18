pipeline {
  agent any
  stages {
    stage('Check Params') {
      steps {
        script {
          params.each {
            echo it
          }
        }
      }
    }
  }
}
