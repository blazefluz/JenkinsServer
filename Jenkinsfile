pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'Hello world $BUILD_NUMBER of $DEMO'
      }
    }

  }
  environment {
    Demo = '1'
  }
}