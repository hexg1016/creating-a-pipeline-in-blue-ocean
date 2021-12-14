pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
  environment {
    image = 'node:6-alpine'
    args = '-p 3000:3000'
  }
}