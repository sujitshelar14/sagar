pipeline {
  agent any
  stages {
    stage('pipe1') {
      parallel {
        stage('pipe1') {
          steps {
            echo 'ok'
          }
        }

        stage('pipe2') {
          steps {
            echo 'hi1'
          }
        }

      }
    }

  }
}