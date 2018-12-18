pipeline {
  agent any
  stages {
    stage('Check Params') {
      steps {
        script {
          this.binding.variables.each {k,v -> println "$k = $v"}
        }
      }
    }
  }
}
