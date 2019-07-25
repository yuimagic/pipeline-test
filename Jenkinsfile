pipeline {
  agent none
  stages {
    stage('build') {
      agent {
        node {
          label 'sirg'
        }

      }
      steps {
        echo 'this is a build step'
      }
    }
    stage('test') {
      steps {
        echo 'this is a test step'
      }
    }
  }
}