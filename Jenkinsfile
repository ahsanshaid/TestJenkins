pipeline {
  agent any
  stages {
    stage('Build Bar') {
      steps {
        bat 'Build'
      }
    }

    stage('Deploy on Sandbox') {
      steps {
        bat 'DeploySandbox.bat'
      }
    }

  }
}