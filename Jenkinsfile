pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'start build'
        sh 'git pull'
        sh 'python testpy.py'
        sh '''pwd
cd /home/roo/Desktop/Joky/work/slots/dev
ls'''
        sh 'cd /home/roo/Desktop/Joky/work/slots/dev'
        sh 'ls'
      }
    }
  }
}