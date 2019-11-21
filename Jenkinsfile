pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        withAnt(installation: 'D:\\Tutorials\\Jenkins\\Build.xml', jdk: '%JAVA_HOME%')
      }
    }

  }
}