pipeline {
  agent any
  stages {
    stage('scm-checkout') {
      steps {
        git(url: 'https://gist.github.com/forked', branch: 'master')
      }
    }

  }
}