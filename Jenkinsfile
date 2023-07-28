pipeline {
  agent any
  stages {
    stage('check out code') {
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