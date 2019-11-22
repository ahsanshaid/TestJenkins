pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'D:\\Tutorials\\Jenkins\\BuildBar.bat'
      }
    }

    stage('Deploy on SandBox') {
      steps {
        bat 'D:\\Tutorials\\Jenkins\\DeploySandbox.bat'
      }
    }

  }
}