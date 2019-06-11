pipeline {
  agent any
  stages {
    stage('git repo') {
      steps {
        git(url: 'https://github.com/lotus9229/github-maven-example', branch: 'master')
      }
    }
    stage('Build') {
      steps {
        sh 'bat "mvn clean -f github-maven-example_master"'
      }
    }
  }
}