pipeline {
  agent any
  stages {
    stage('New Bulid') {
      steps {
        echo 'HI how are you'
        echo 'My Nmae Mohamed Hassan'
      }
    }

    stage('Test New Stage') {
      steps {
        sh 'echo \'mohamed hassan saber\''
      }
    }

    stage('Deploy') {
      steps {
        input(message: 'Are you ready to deploy', ok: 'yes im')
      }
    }

  }
}