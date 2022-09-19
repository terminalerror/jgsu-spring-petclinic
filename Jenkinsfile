pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello World'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing Apps'
          }
        }

      }
    }

    stage('') {
      steps {
        echo 'Deploy'
      }
    }

  }
}