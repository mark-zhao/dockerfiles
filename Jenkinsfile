pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('step1') {
          steps {
            sh 'echo `pwd`'
          }
        }
        stage('step1.1') {
          steps {
            sh 'echo 2'
          }
        }
        stage('xxx') {
          steps {
            sh 'echo xxx'
          }
        }
      }
    }
    stage('step 3') {
      steps {
        sh 'echo 3'
      }
    }
  }
}