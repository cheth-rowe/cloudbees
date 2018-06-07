pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello (whirled) ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}