pipeline {
  agent none {
    stages {
      stage('Build') {
        steps {
          echo 'Running Build Automation'
          sh './gradlew build --no-daemon'
          archiveArtifacts:'dist/trainSchedule'
          }
        }
    }
  }
}
