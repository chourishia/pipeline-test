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
        stage('Build') {
          steps {
            echo 'Build, but only for branch HOB1-001'
          }
        }        
      }
    }
  }
}
