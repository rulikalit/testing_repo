pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo "halo"'
          }
        }
        stage('test') {
          steps {
            sh 'echo "hallo"'
          }
        }
      }
    }
  }
}