pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'start build<a href="http://www.w3school.com.cn">W3School</a>'
        sh 'git pull'
        sh 'python testpy.py'
        sh '''pwd
cd /home/roo/Desktop/Joky/work/slots/dev
ls'''
      }
    }
  }
}