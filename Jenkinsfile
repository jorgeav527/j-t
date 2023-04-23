pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'ls'
      }
    }

    stage('echo') {
      steps {
        echo 'echo holaaaaaa'
        sh 'ls'
        sh 'sh "helloooo"'
      }
    }

    stage('build fly') {
      steps {
        sh 'sleep 5'
        sh 'echo Success!'
      }
    }

  }
  environment {
    name = 'jorge ramiro alrcon vargas'
    db = 'linode-sss-xxx-llll'
  }
}