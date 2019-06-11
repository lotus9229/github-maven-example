pipeline {
  agent any
  stages {
    stage('git repo') {
      steps {
        git(url: 'https://github.com/lotus9229/github-maven-example', branch: 'master')
      }
    }
  }
}