pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        withAnt(installation: 'Build.xml', jdk: '%JAVA_HOME%')
      }
    }

  }
}