pipeline {
  agent any
  stages {
    stage('echo ') {
      steps {
        sh '''pwd;
env;'''
      }
    }
    stage('Build a pdf') {
      parallel {
        stage('Build a pdf') {
          steps {
            sh 'echo "Building a pdf"'
          }
        }
        stage('Build an html') {
          steps {
            sh 'echo"Building an html"'
          }
        }
      }
    }
  }
}