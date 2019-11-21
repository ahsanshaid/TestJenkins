pipeline {
  agent any
  stages {
    stage('Build Bar') {
      steps {
        bat 'Build.bat'
      }
    }

    stage('Deploy on Sandbox') {
      steps {
        bat 'DeploySandbox.bat'
      }
    }

  }
}