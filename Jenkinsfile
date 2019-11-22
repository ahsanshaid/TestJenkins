pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        withAnt(installation: 'Build.xml')
      }
    }

  }
}