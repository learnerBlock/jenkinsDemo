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
      }
    }
  }
  environment {
    name = '111'
  }
}