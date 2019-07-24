pipeline {
  agent {
    node {
      label 'master'
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
    stage('deploy') {
      steps {
        echo 'this is a deploy step'
      }
    }
  }
}