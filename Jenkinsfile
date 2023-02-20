pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'Hello world'
          }
        }

        stage('test2') {
          steps {
            sh 'echo "Hi from shell script"'
          }
        }

      }
    }

  }
}