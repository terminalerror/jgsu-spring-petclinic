pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Hello') {
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

    stage('Deploy') {
      steps {
        echo 'Deploy file:///home/terminal/Downloads/GitHubProjects/forked/jgsu-spring-petclinic/.git test'
      }
    }

  }
}