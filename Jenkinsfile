pipeline {
    agent any
  options {
    buildDiscarder(logRotator(numToKeepStr: '5'))
    disableConcurrentBuilds()
  }
  stages {
    stage('Helloo') {
      steps {
        sh 'echo "Hello World from the Pipeline"'
      }
    }
  }