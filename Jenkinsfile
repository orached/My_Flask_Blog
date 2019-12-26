pipeline {
  agent any
  stages {
    stage('stage one') {
      steps {
        echo 'In my first step, i want to pull code from repo'
        git(poll: true, url: 'https://github.com/orached/My_Flask_Blog', branch: 'master')
      }
    }

  }
}