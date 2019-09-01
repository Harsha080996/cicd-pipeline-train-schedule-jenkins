pipeline {
  agent any
  stages {
    stage ('Build') {
      echo 'Running Build automation'
      sh './gradlew build --nodaemon'
      archiveArtifacts artifacts : 'dist/tainSchedule.zip'
    }
  }
  
}
