pipeline {
  agent any
  stages {
    stage('Fluffy Build') {
      steps {
        echo 'Placeholder'
        sh 'echo Edited Placeholder.'
      }
    }

    stage('Fluffy Test') {
      steps {
        sh 'sleep 20'
        sh 'echo Success!'
      }
    }

    stage('Fluffy Deploy') {
      steps {
        echo 'hello'
        sh 'echo $NAME'
      }
    }

  }
  environment {
    NAME = 'jorge ramiro alrcon vargas'
    db = 'linode-sss-xxx-llll'
    new_branch = 'xxx'
  }
}