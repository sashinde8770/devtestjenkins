pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo "build"'
          }
        }

        stage('test') {
          steps {
            echo 'Hello world'
          }
        }

      }
    }

  }
}