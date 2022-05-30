pipeline {
    agent any
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
    disableConcurrentBuilds()
  }
  stages {
    stage('Helloo') {
      steps {
        echo "Hello World!"
      }
    }
  }