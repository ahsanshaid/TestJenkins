pipeline {
  agent any
  stages {
    stage('Build Bar') {
      steps {
        bat 'D:\\Tutorials\\Jenkins\\Build.bat'
      }
    }

    stage('Deploy on Sandbox') {
      steps {
        bat 'D:\\Tutorials\\Jenkins\\DeploySandbox.bat'
      }
    }

  }
}