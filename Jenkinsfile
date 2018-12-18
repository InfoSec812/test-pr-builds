pipeline {
  agent any
  stages {
    stage('Check Params') {
      steps {
        script {
          params.each { param ->
            println param
          }
        }
      }
    }
  }
}
