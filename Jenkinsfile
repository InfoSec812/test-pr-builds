pipeline {
  agent any
  stages {
    stage('Check Params') {
      steps {
        script {
          parameters.properties.each {
            echo it
          }
        }
      }
    }
  }
}
