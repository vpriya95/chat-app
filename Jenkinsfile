pipeline {
  agent {
    node {
      label 'start'
    }

  }
  stages {
    stage('test') {
      steps {
        sh '''npm install 

npm test'''
      }
    }
  }
}