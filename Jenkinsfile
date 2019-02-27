pipeline {
  agent any
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            echo 'Hello word'
          }
        }
        stage('Checkout Cocde') {
          steps {
            echo 'I am in Checkout process'
          }
        }
      }
    }
  }
}