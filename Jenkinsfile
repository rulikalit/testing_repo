pipeline {
  agent any
  stages {
    stage('Checkout branch') {
      parallel {
        stage('Checkout branch') {
          steps {
            echo 'Checkout branch'
          }
        }
        stage('Prepare ENV') {
          environment {
            asdas = 'asdasd'
            asdasd = 'asdasdasdas'
          }
          steps {
            echo 'being set'
          }
        }
      }
    }
  }
}