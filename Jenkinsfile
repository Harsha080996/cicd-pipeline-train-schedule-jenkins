pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      echo 'Running Build automation'
      sh './gradlew build --nodaemon'
      archiveArtifacts artifacts : 'dist/tainSchedule.zip'
      }
    }
  }
  
}
