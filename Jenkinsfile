pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('step1') {
          steps {
            sh 'echo 1'
          }
        }
        stage('step1.1') {
          steps {
            sh 'echo 2'
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