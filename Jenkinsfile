pipeline {
  agent any
  stages {
    stage('Say Hello') {
      parallel {
        stage('Say Hello') {
          steps {
            echo 'HELLO'
          }
        }
        stage('java-version') {
          steps {
            sh 'java -version'
          }
        }
      }
    }
  }
  environment {
    hello = ''
  }
}