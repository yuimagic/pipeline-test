pipeline {
  agent {
    node {
      label 'sirg'
    }

  }
  stages {
    stage('build') {
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