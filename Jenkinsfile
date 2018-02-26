pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'start build'
        sh 'git pull'
        sh 'python testpy.py'
        sh 'pwd'
      }
    }
  }
}