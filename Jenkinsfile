pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        sh '''#!/bin/bash
                    
                    set +x
                    echo "THIS IS A TEST FOR THE JENKINS PIPELINE"
                    set -x
                '''
      }
    }

  }
  environment {
    ENGINE = 'fot'
    VERSION = '1.0.2'
    RPM_FILE = ''
  }
}