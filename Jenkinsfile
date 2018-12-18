pipeline {
  agent any
  stages {
    stage('Check Params') {
      steps {
        script {
          env.properties.each {
            echo it
          }
        }
      }
    }
  }
}
