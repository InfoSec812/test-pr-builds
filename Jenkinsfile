import groovy.json.JsonOutput

pipeline {
  agent any
  stages {
    stage('Check Params') {
      steps {
        script {
          def json = JsonOutput.toJson(env)
          println JsonOutput.prettyPrint(json)
          json = JsonOutput.toJson(params)
          println JsonOutput.prettyPrint(json)
        }
      }
    }
  }
}
