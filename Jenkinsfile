pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'start build'
        sh 'ls'
        sh 'python testpy.py'
      }
    }
  }
}