import groovy.json.JsonOutput

pipeline {
  agent any
  parameters {
    payload: ''
  }
  stages {
    stage('Check Params') {
      steps {
        script {
          def json = JsonOutput.toJson(env)
          println JsonOutput.prettyPrint(json)
          json = JsonOutput.toJson(payload)
          println JsonOutput.prettyPrint(json)
        }
      }
    }
  }
}
