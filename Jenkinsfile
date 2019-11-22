pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        withAnt(installation: '%ANT_HOME%')
      }
    }

  }
}