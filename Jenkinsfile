pipeline {
  agent any
  stages {
    stage('Get the source') {
      steps {
        git(url: 'https://github.com/emrys-s/devops_logbook', branch: 'master')
      }
    }
  }
}