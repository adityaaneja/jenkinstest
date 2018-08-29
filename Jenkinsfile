pipeline {
  agent any
  stages {
    stage('Shell script Stage') {
      agent any
      steps {
        sh '''#!/bin/bash
echo "Hello World -aa-"'''
        timeout(time: 10)
      }
    }
    stage('Done Stage') {
      steps {
        echo 'DONE!!!!'
      }
    }
  }
}