import groovy.json.JsonOutput

pipeline {
  agent any
  stages {
    stage('Check Params') {
      steps {
        script {
          params.each { param ->
            def json = JsonOutput.toJson(params)
            println JsonOutput.prettyPrint(json)
          }
        }
      }
    }
  }
}
