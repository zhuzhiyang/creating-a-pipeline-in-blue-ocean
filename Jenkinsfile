pipeline {
  agent any
  stages {
    stage('Build') {
      agent {
        node {
          label 'docker-nginx'
        }

      }
      steps {
        sh 'npm install'
      }
    }

  }
}