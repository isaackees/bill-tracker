pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(url: 'https://github.com/isaackees/bill-tracker', branch: 'main')
      }
    }

    stage('logs') {
      steps {
        sh 'la -la'
      }
    }

  }
}