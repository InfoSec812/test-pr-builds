pipeline {
  agent any
  stages {
    stage('Check Params') {
      steps {
        script {
          params.properties.each {
            echo it
          }
        }
      }
    }
  }
}
