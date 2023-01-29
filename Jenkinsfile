pipeline {
  agent any
  stages {
    stage('Check-out code') {
      steps {
        git(url: 'https://github.com/eduardorezaghi/curriculum-app', branch: 'dev')
      }
    }

    stage('Display Node.js version') {
      steps {
        sh 'node --version'
      }
    }

  }
}