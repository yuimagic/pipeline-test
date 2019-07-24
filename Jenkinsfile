pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo \'this is a build step\''
      }
    }
    stage('test') {
      steps {
        sh 'echo \'this is a test step\''
      }
    }
    stage('deploy') {
      steps {
        sh 'echo \'this is a deploy step\''
      }
    }
  }
}