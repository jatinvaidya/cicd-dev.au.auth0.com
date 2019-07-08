pipeline {
  agent any
  stages {
    stage('check file') {
      steps {
        sh 'cat tenant.json'
      }
    }
    stage('check file2') {
      steps {
        sh 'cat pages/password_reset.json'
      }
    }
  }
}