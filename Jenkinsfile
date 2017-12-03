pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            echo 'first message'
          }
        }
        stage('seond') {
          steps {
            git 'https://github.com/ledging/cse.git'
          }
        }
      }
    }
  }
}