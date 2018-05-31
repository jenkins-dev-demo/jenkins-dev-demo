pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'HELLO'
      }
    }
    stage('Java_Version') {
      steps {
        sh 'java -version'
      }
    }
  }
  environment {
    hello = ''
  }
}