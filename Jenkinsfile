pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation y probando ejecutando a mano'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
