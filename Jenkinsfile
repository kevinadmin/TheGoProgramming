pipeline {
  agent any
  stages {
    stage('pull code') {
      steps {
        sh '''#!/bin/bash


echo  start pull code '''
      }
    }
    stage('build imge') {
      steps {
        echo 'build images'
      }
    }
    stage('done') {
      steps {
        echo 'done'
      }
    }
  }
}