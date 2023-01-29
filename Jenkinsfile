pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''git pull
npm i 
ls -ltr
'''
      }
    }

    stage('Test') {
      steps {
        sh '''npm test
'''
      }
    }

    stage('Deliver') {
      steps {
        sh '''echo "Deliver to ..."
'''
      }
    }

  }
}