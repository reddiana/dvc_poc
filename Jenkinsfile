pipeline {
  agent any
  stages {
    stage('get_code') {
      steps {
        git(url: 'https://github.com/reddiana/dvc_poc.git', branch: 'master')
        sh 'docker run --rm --it ubuntu date'
      }
    }

  }
}