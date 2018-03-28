pipeline {
  agent any
  stages {
    stage('Get the source') {
      parallel {
        stage('Get the source') {
          steps {
            git(url: 'https://github.com/emrys-s/devops_logbook', branch: 'master')
          }
        }
        stage('echo ') {
          steps {
            sh '''pwd;
env;'''
          }
        }
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