pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'hello it works'
        sh 'pwd'
      }
    }

    stage('validate') {
      steps {
        sh 'cd bin/'
      }
    }

  }
}