pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'this is a build step'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'this is a test step'
          }
        }

        stage('test1') {
          steps {
            echo 'it is test1'
          }
        }

      }
    }

  }
}