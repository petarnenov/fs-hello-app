pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''npm i
npm start'''
      }
    }

    stage('Test') {
      steps {
        sh '''npm test
'''
      }
    }

  }
}