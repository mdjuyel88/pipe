pipeline {
  agent none
  stages {
    stage('builed') {
      steps {
        sh 'echo "hello server building"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "testing serv"'
      }
    }

    stage('deploy') {
      steps {
        sh '"echo deployed"'
      }
    }

  }
  environment {
    helloworld = 'hello'
  }
}