pipeline {
  agent any
  stages {
    stage('first') {
      parallel {
        stage('first') {
          steps {
            echo 'done my friend'
          }
        }
        stage('first/2') {
          steps {
            echo 'second'
          }
        }
      }
    }
  }
}