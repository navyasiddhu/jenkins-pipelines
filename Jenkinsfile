pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo "its working"'
        sleep 10
        echo 'This is done'
      }
    }

  }
  environment {
    env = 'dev'
  }
}