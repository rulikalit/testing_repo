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
    stage('testt') {
      parallel {
        stage('testt') {
          steps {
            echo 'helo'
          }
        }
        stage('hello') {
          steps {
            echo 'hell'
          }
        }
      }
    }
    stage('sd') {
      parallel {
        stage('sd') {
          steps {
            echo 'diterima'
          }
        }
        stage('sda') {
          steps {
            echo 'ditolak'
          }
        }
      }
    }
    stage('finish') {
      steps {
        echo 'selesai'
      }
    }
  }
}