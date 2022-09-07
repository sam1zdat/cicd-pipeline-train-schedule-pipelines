pipeline {
  agant any
  stages {
    steps {
      stage('Build') {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtufacts artifacts:'dist/trainSchedule.zip'
      }
    }
  }
}
