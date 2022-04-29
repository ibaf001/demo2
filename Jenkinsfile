pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'this is my build $BUILD of job called $DEMO_NUMBER'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}