pipeline {
  agent any
  stages {
    stage('111') {
      agent any
      environment {
        aaaa = '222'
      }
      steps {
        sh 'echo "hello" name'
        echo 'jenkins'
        sleep 3
      }
    }
  }
  environment {
    name = '111'
  }
}